<template>
  <div class="tab-pane fade h-100" role="tabpanel">
    <div class="d-flex flex-column h-100">
      <div class="hide-scrollbar">
        <div class="container-fluid py-6">
          <!-- Title -->
          <h2 class="font-bold mb-6">Chats</h2>
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

          <!-- Favourites -->
          <div class="text-center hide-scrollbar d-flex my-7" data-horizontal-scroll="">
            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm avatar-online mb-3">
                <img class="avatar-img" :src="avatarMale" alt="Image Description" />
              </div>
              <div class="small">William</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm avatar-online mb-3">
                <img class="avatar-img" :src="avatarFemale" alt="Image Description" />
              </div>
              <div class="small">Simon</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm avatar-online mb-3">
                <img class="avatar-img" :src="avatarMale" alt="Image Description" />
              </div>
              <div class="small">Thomas</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm avatar-online mb-3">
                <img class="avatar-img" :src="avatarFemale" alt="Image Description" />
              </div>
              <div class="small">Zane</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm mb-3">
                <img class="avatar-img" :src="avatarMale" alt="Image Description" />
              </div>
              <div class="small">Thomas</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm mb-3">
                <img class="avatar-img" :src="avatarFemale" alt="Image Description" />
              </div>
              <div class="small">William</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm mb-3">
                <img class="avatar-img" :src="avatarMale" alt="Image Description" />
              </div>
              <div class="small">Simon</div>
            </a>

            <a href="#" class="d-block text-reset mr-7 mr-lg-6">
              <div class="avatar avatar-sm mb-3">
                <img class="avatar-img" :src="avatarFemale" alt="Image Description" />
              </div>
              <div class="small">Thomas</div>
            </a>
          </div>
          <!-- Favourites -->

          <!-- Chats -->
          <nav class="nav d-block list-discussions-js mb-n6">
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="chat-1.html">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarMale" alt="Bootstrap Themes" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Bootstrap Themes</h6>
                        <p class="small text-muted text-nowrap ml-4">10:42 am</p>
                      </div>
                      <div class="text-truncate">
                        Anna Bridges: Hey, Maher! How are you? The weather is great isn't it?
                      </div>
                    </div>
                  </div>
                </div>

                <div class="badge badge-circle badge-primary badge-border-light badge-top-right">
                  <span>3</span>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="chat-2.html">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar avatar-online mr-5">
                      <img class="avatar-img" :src="avatarFemale" alt="Anna Bridges" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Anna Bridges</h6>
                        <p class="small text-muted text-nowrap ml-4">10:42 am</p>
                      </div>
                      <div class="text-truncate">
                        is typing<span class="typing-dots"><span>.</span><span>.</span><span>.</span></span>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarMale" alt="Simon Hensley" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Simon Hensley</h6>
                        <p class="small text-muted text-nowrap ml-4">10:38 am</p>
                      </div>
                      <div class="text-truncate">I’m sorry, this question would be out of my expertise.</div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarFemale" alt="William Wright" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">William Wright</h6>
                        <p class="small text-muted text-nowrap ml-4">10:20 am</p>
                      </div>
                      <div class="text-truncate">Hello! Let me transfer you to the marketing department.</div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarMale" alt="Leslie Sutton" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Leslie Sutton</h6>
                        <p class="small text-muted text-nowrap ml-4">09:55 am</p>
                      </div>
                      <div class="text-truncate">
                        <h6 class="d-inline">You:</h6>
                        I’m sorry, I don’t have the information on that.
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarFemale" alt="Matthew Wiggins" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Matthew Wiggins</h6>
                        <p class="small text-muted text-nowrap ml-4">09:25 am</p>
                      </div>
                      <div class="text-truncate">Matthew, let me transfer you to the marketing department.</div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarMale" alt="Thomas Walker" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Thomas Walker</h6>
                        <p class="small text-muted text-nowrap ml-4">09:00 am</p>
                      </div>
                      <div class="text-truncate">
                        I am really sorry to hear that. Is there anything I can do to help you?
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarFemale" alt="Zane Mayes" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Zane Mayes</h6>
                        <p class="small text-muted text-nowrap ml-4">08:05 am</p>
                      </div>
                      <div class="text-truncate">That is a good question, let me find out for you.</div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
            <!-- Chat link -->
            <a class="text-reset nav-link p-0 mb-6" href="#">
              <div class="card card-active-listener">
                <div class="card-body">
                  <div class="media">
                    <div class="avatar mr-5">
                      <img class="avatar-img" :src="avatarMale" alt="Brian Dawson" />
                    </div>

                    <div class="media-body overflow-hidden">
                      <div class="d-flex align-items-center mb-1">
                        <h6 class="text-truncate mb-0 mr-auto">Brian Dawson</h6>
                        <p class="small text-muted text-nowrap ml-4">08:00 am</p>
                      </div>
                      <div class="text-truncate">I’m not sure, but let me find out for you.</div>
                    </div>
                  </div>
                </div>
              </div>
            </a>
            <!-- Chat link -->
          </nav>
          <!-- Chats -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import avatarMale from '@/assets/images/avatar_male.jpg';
import avatarFemale from '@/assets/images/avatar_female.jpg';

export default {
  name: 'm-conversations',
  data() {
    return {
      avatarMale,
      avatarFemale,
    };
  },
};
</script>
