<template>
  <div class="tab-pane fade h-100" role="tabpanel">
    <div class="d-flex flex-column h-100">
      <div class="hide-scrollbar">
        <div class="container-fluid py-6">
          <!-- Title -->
          <h2 class="font-bold mb-6">Profile</h2>
          <!-- Title -->

          <!-- Search -->
          <form class="mb-6">
            <div class="input-group">
              <input
                type="text"
                class="form-control form-control-lg"
                placeholder="Search for messages or users..."
                aria-label="Search for messages or users..."
              />
              <div class="input-group-append">
                <button class="btn btn-lg btn-ico btn-secondary btn-minimal" type="submit">
                  <i class="fe-search"></i>
                </button>
              </div>
            </div>
          </form>
          <!-- Search -->

          <!-- Card -->
          <div class="card mb-6">
            <div class="card-body">
              <div class="text-center py-6">
                <!-- Photo -->
                <div class="avatar avatar-xl mb-5">
                  <img class="avatar-img" :src="avatarMale" alt="" />
                </div>

                <h5>Matthew Wiggins</h5>
                <p class="text-muted">Bootstrap is an open source toolkit for developing web with HTML.</p>
              </div>
            </div>
          </div>
          <!-- Card -->

          <!-- Card -->
          <div class="card mb-6">
            <div class="card-body">
              <ul class="list-group list-group-flush">
                <li class="list-group-item px-0 py-6">
                  <div class="media align-items-center">
                    <div class="media-body">
                      <p class="small text-muted mb-0">Country</p>
                      <p>Warsaw, Poland</p>
                    </div>
                    <i class="text-muted icon-sm fe-globe"></i>
                  </div>
                </li>

                <li class="list-group-item px-0 py-6">
                  <div class="media align-items-center">
                    <div class="media-body">
                      <p class="small text-muted mb-0">Phone</p>
                      <p>+39 02 87 21 43 19</p>
                    </div>
                    <i class="text-muted icon-sm fe-mic"></i>
                  </div>
                </li>

                <li class="list-group-item px-0 py-6">
                  <div class="media align-items-center">
                    <div class="media-body">
                      <p class="small text-muted mb-0">Email</p>
                      <p>anna@gmail.com</p>
                    </div>
                    <i class="text-muted icon-sm fe-mail"></i>
                  </div>
                </li>

                <li class="list-group-item px-0 py-6">
                  <div class="media align-items-center">
                    <div class="media-body">
                      <p class="small text-muted mb-0">Time</p>
                      <p>10:03 am</p>
                    </div>
                    <i class="text-muted icon-sm fe-clock"></i>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <!-- Card -->

          <!-- Card -->
          <div class="card mb-6">
            <div class="card-body">
              <ul class="list-group list-group-flush">
                <li class="list-group-item px-0 py-6">
                  <a href="#" class="media text-muted">
                    <div class="media-body align-self-center">Twitter</div>
                    <i class="icon-sm fe-twitter"></i>
                  </a>
                </li>

                <li class="list-group-item px-0 py-6">
                  <a href="#" class="media text-muted">
                    <div class="media-body align-self-center">Facebook</div>
                    <i class="icon-sm fe-facebook"></i>
                  </a>
                </li>

                <li class="list-group-item px-0 py-6">
                  <a href="#" class="media text-muted">
                    <div class="media-body align-self-center">Github</div>
                    <i class="icon-sm fe-github"></i>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <!-- Card -->

          <div class="form-row">
            <div class="col">
              <!-- Button -->
              <button type="button" class="btn btn-lg btn-block btn-basic d-flex align-items-center">
                Settings
                <span class="fe-settings ml-auto"></span>
              </button>
            </div>

            <div class="col">
              <!-- Button -->
              <button
                @click.prevent="logout"
                type="button"
                class="btn btn-lg btn-block btn-basic d-flex align-items-center"
              >
                Logout
                <span class="fe-log-out ml-auto"></span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import avatarMale from '@/assets/images/avatar_male.jpg';
import { mapActions } from 'vuex';

export default {
  name: 'm-profile',
  data() {
    return {
      avatarMale,
    };
  },
  methods: {
    ...mapActions('auth', ['LOGOUT']),
    logout() {
      this.LOGOUT();
    },
  },
};
</script>
