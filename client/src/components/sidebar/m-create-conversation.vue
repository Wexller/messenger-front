<template>
  <div class="tab-pane fade h-100" role="tabpanel">
    <div class="d-flex flex-column h-100">
      <div class="hide-scrollbar">
        <div class="container-fluid py-6">
          <!-- Title -->
          <h2 class="font-bold mb-6">Create group</h2>
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

          <!-- Tabs -->
          <ul class="nav nav-tabs nav-justified mb-6" role="tablist">
            <li class="nav-item">
              <a href="#create-group-details" class="nav-link active" data-toggle="tab" role="tab" aria-selected="true"
                >Details</a
              >
            </li>

            <li class="nav-item">
              <a href="#create-group-members" class="nav-link" data-toggle="tab" role="tab" aria-selected="false"
                >Members</a
              >
            </li>
          </ul>
          <!-- Tabs -->

          <!-- Create chat -->
          <div class="tab-content" role="tablist">
            <!-- Chat details -->
            <div id="create-group-details" class="tab-pane fade show active" role="tabpanel">
              <form action="#">
                <div class="form-group">
                  <label class="small">Photo</label>
                  <div class="position-relative text-center bg-secondary rounded p-6">
                    <div class="avatar bg-primary text-white mb-5">
                      <i class="icon-md fe-image"></i>
                    </div>

                    <p class="small text-muted mb-0">
                      You can upload jpg, gif or png files. <br />
                      Max file size 3mb.
                    </p>
                    <input id="upload-chat-photo" class="d-none" type="file" />
                    <label class="stretched-label mb-0" for="upload-chat-photo"></label>
                  </div>
                </div>

                <div class="form-group">
                  <label class="small" for="new-chat-title">Name</label>
                  <input
                    class="form-control form-control-lg"
                    name="new-chat-title"
                    id="new-chat-title"
                    type="text"
                    placeholder="Group Name"
                  />
                </div>

                <div class="form-group">
                  <label class="small" for="new-chat-topic">Topic (optional)</label>
                  <input
                    class="form-control form-control-lg"
                    name="new-chat-topic"
                    id="new-chat-topic"
                    type="text"
                    placeholder="Group Topic"
                  />
                </div>

                <div class="form-group mb-0">
                  <label class="small" for="new-chat-description">Description</label>
                  <textarea
                    class="form-control form-control-lg"
                    name="new-chat-description"
                    id="new-chat-description"
                    rows="6"
                    placeholder="Group Description"
                  ></textarea>
                </div>
              </form>
            </div>
            <!-- Chat details -->

            <!-- Chat Members -->
            <div id="create-group-members" class="tab-pane fade" role="tabpanel">
              <nav class="list-group list-group-flush mb-n6">
                <div class="mb-6">
                  <small class="text-uppercase">A</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar avatar-online mr-5">
                        <img class="avatar-img" :src="avatarMale" alt="Anna Bridges" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">Anna Bridges</h6>
                        <small class="text-muted">Online</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-1" type="checkbox" />
                          <label class="custom-control-label" for="id-user-1"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-1"></label>
                </div>
                <!-- Friend -->

                <div class="mb-6">
                  <small class="text-uppercase">B</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarFemale" alt="Brian Dawson" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">Brian Dawson</h6>
                        <small class="text-muted">last seen 2 hours ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-2" type="checkbox" />
                          <label class="custom-control-label" for="id-user-2"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-2"></label>
                </div>
                <!-- Friend -->

                <div class="mb-6">
                  <small class="text-uppercase">L</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarMale" alt="Leslie Sutton" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">Leslie Sutton</h6>
                        <small class="text-muted">last seen 3 days ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-3" type="checkbox" />
                          <label class="custom-control-label" for="id-user-3"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-3"></label>
                </div>
                <!-- Friend -->

                <div class="mb-6">
                  <small class="text-uppercase">M</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarFemale" alt="Matthew Wiggins" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">Matthew Wiggins</h6>
                        <small class="text-muted">last seen 3 days ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-4" type="checkbox" />
                          <label class="custom-control-label" for="id-user-4"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-4"></label>
                </div>
                <!-- Friend -->

                <div class="mb-6">
                  <small class="text-uppercase">S</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarMale" alt="Simon Hensley" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">Simon Hensley</h6>
                        <small class="text-muted">last seen 3 days ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-5" type="checkbox" />
                          <label class="custom-control-label" for="id-user-5"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-5"></label>
                </div>
                <!-- Friend -->

                <div class="mb-6">
                  <small class="text-uppercase">W</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarFemale" alt="William Wright" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">William Wright</h6>
                        <small class="text-muted">last seen 3 days ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-6" type="checkbox" />
                          <label class="custom-control-label" for="id-user-6"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-6"></label>
                </div>
                <!-- Friend --><!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarMale" alt="William Greer" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">William Greer</h6>
                        <small class="text-muted">last seen 10 minutes ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-7" type="checkbox" />
                          <label class="custom-control-label" for="id-user-7"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-7"></label>
                </div>
                <!-- Friend -->

                <div class="mb-6">
                  <small class="text-uppercase">Z</small>
                </div>

                <!-- Friend -->
                <div class="card mb-6">
                  <div class="card-body">
                    <div class="media">
                      <div class="avatar mr-5">
                        <img class="avatar-img" :src="avatarFemale" alt="Zane Mayes" />
                      </div>

                      <div class="media-body align-self-center mr-6">
                        <h6 class="mb-0">Zane Mayes</h6>
                        <small class="text-muted">last seen 3 days ago</small>
                      </div>

                      <div class="align-self-center ml-auto">
                        <div class="custom-control custom-checkbox">
                          <input class="custom-control-input" id="id-user-8" type="checkbox" />
                          <label class="custom-control-label" for="id-user-8"></label>
                        </div>
                      </div>
                    </div>
                  </div>

                  <!-- Label -->
                  <label class="stretched-label" for="id-user-8"></label>
                </div>
                <!-- Friend -->
              </nav>
            </div>
            <!-- Chat Members -->
          </div>
          <!-- Create chat -->
        </div>
      </div>

      <!-- Button -->
      <div class="pb-6">
        <div class="container-fluid">
          <button class="btn btn-lg btn-primary btn-block" type="submit">Create group</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import avatarMale from '@/assets/images/avatar_male.jpg';
import avatarFemale from '@/assets/images/avatar_female.jpg';

export default {
  name: 'm-create-conversation',

  data() {
    return {
      avatarMale,
      avatarFemale,
    };
  },
};
</script>
