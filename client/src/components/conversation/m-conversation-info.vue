<template>
  <div id="chat-2-info" class="chat-sidebar">
    <div class="d-flex h-100 flex-column">
      <!-- Header -->
      <div class="border-bottom py-4 py-lg-6">
        <div class="container-fluid">
          <ul class="nav justify-content-between align-items-center">
            <!-- Close sidebar -->
            <li class="nav-item list-inline-item">
              <a class="nav-link text-muted px-0" href="#" data-chat-sidebar-close="">
                <i class="icon-md fe-chevron-left"></i>
              </a>
            </li>

            <!-- Title(mobile) -->
            <li class="text-center d-block d-lg-none">
              <h6 class="mb-n2">Anna Bridges</h6>
              <small class="text-muted">Chat Details</small>
            </li>

            <!-- Dropdown -->
            <li class="nav-item list-inline-item">
              <div class="dropdown">
                <a
                  class="nav-link text-muted px-0"
                  href="#"
                  data-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                >
                  <i class="icon-md fe-sliders"></i>
                </a>
                <div class="dropdown-menu">
                  <a class="dropdown-item d-flex align-items-center" href="#">
                    Mute
                    <span class="ml-auto fe-bell"></span>
                  </a>
                  <a class="dropdown-item d-flex align-items-center" href="#">
                    Delete
                    <span class="ml-auto fe-trash-2"></span>
                  </a>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <!-- Header -->

      <!-- Body -->
      <div class="hide-scrollbar flex-fill">
        <div class="border-bottom text-center py-9 px-10">
          <!-- Photo -->
          <div class="avatar avatar-xl mx-5 mb-5">
            <img class="avatar-img" :src="avatarFemale" alt="" />
          </div>
          <h5>Anna Bridges</h5>
          <p class="text-muted">Bootstrap is an open source toolkit for developing web with HTML, CSS, and JS.</p>
        </div>

        <!-- Navs -->
        <div class="nav nav-tabs nav-justified bg-light rounded-0" role="tablist">
          <a
            class="nav-item nav-link active"
            href="#chat-2-user-details"
            data-toggle="tab"
            aria-selected="true"
            role="tab"
            >Details</a
          >
          <a class="nav-item nav-link" href="#chat-2-user-files" data-toggle="tab" role="tab">Files</a>
        </div>
        <!-- Navs -->

        <div class="tab-content" role="tablist">
          <!-- Details -->
          <div id="chat-2-user-details" class="tab-pane fade show active" role="tabpanel">
            <ul class="list-group list-group-flush mb-8">
              <li class="list-group-item py-6">
                <div class="media align-items-center">
                  <div class="media-body">
                    <p class="small text-muted mb-0">Country</p>
                    <p>Warsaw, Poland</p>
                  </div>
                  <i class="text-muted icon-sm fe-globe"></i>
                </div>
              </li>

              <li class="list-group-item py-6">
                <div class="media align-items-center">
                  <div class="media-body">
                    <p class="small text-muted mb-0">Phone</p>
                    <p>+39 02 87 21 43 19</p>
                  </div>
                  <i class="text-muted icon-sm fe-mic"></i>
                </div>
              </li>

              <li class="list-group-item py-6">
                <div class="media align-items-center">
                  <div class="media-body">
                    <p class="small text-muted mb-0">Email</p>
                    <p>anna@gmail.com</p>
                  </div>
                  <i class="text-muted icon-sm fe-mail"></i>
                </div>
              </li>

              <li class="list-group-item py-6">
                <div class="media align-items-center">
                  <div class="media-body">
                    <p class="small text-muted mb-0">Time</p>
                    <p>10:03 am</p>
                  </div>
                  <i class="text-muted icon-sm fe-clock"></i>
                </div>
              </li>
            </ul>

            <ul class="list-group list-group-flush">
              <li class="list-group-item py-6">
                <a href="#" class="media text-muted">
                  <div class="media-body align-self-center">Twitter</div>
                  <i class="icon-sm fe-twitter"></i>
                </a>
              </li>

              <li class="list-group-item py-6">
                <a href="#" class="media text-muted">
                  <div class="media-body align-self-center">Facebook</div>
                  <i class="icon-sm fe-facebook"></i>
                </a>
              </li>

              <li class="list-group-item py-6">
                <a href="#" class="media text-muted">
                  <div class="media-body align-self-center">Github</div>
                  <i class="icon-sm fe-github"></i>
                </a>
              </li>
            </ul>
          </div>
          <!-- Details -->

          <!-- Files -->
          <div id="chat-2-user-files" class="tab-pane fade" role="tabpanel">
            <ul class="list-group list-group-flush list-group-no-border-first">
              <!-- File -->
              <li class="list-group-item py-6">
                <div class="media">
                  <div class="icon-shape bg-primary text-white mr-5">
                    <i class="fe-paperclip"></i>
                  </div>

                  <div class="media-body align-self-center overflow-hidden">
                    <h6 class="text-truncate mb-0">
                      <a href="#" class="text-reset" title="E5419783-047D-4B4C-B30E-F24DD8247731.JPG"
                        >E5419783-047D-4B4C-B30E-F24DD8247731.JPG</a
                      >
                    </h6>

                    <ul class="list-inline small mb-0">
                      <li class="list-inline-item">
                        <span class="text-muted">79.2 KB</span>
                      </li>
                      <li class="list-inline-item">
                        <span class="text-muted text-uppercase">txt</span>
                      </li>
                    </ul>
                  </div>

                  <div class="align-self-center ml-5">
                    <div class="dropdown">
                      <a
                        href="#"
                        class="btn btn-sm btn-ico btn-link text-muted w-auto"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        aria-expanded="false"
                      >
                        <i class="fe-more-vertical"></i>
                      </a>
                      <div class="dropdown-menu">
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Download <span class="ml-auto fe-download"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Share <span class="ml-auto fe-share-2"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Delete <span class="ml-auto fe-trash-2"></span>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <!-- File -->

              <!-- File -->
              <li class="list-group-item py-6">
                <div class="media">
                  <div class="icon-shape bg-primary text-white mr-5">
                    <i class="fe-paperclip"></i>
                  </div>

                  <div class="media-body align-self-center overflow-hidden">
                    <h6 class="text-truncate mb-0">
                      <a href="#" class="text-reset" title="E5419783-047D-4B4C-B30E-F24DD8247731.JPG"
                        >E5419783-047D-4B4C-B30E-F24DD8247731.JPG</a
                      >
                    </h6>

                    <ul class="list-inline small mb-0">
                      <li class="list-inline-item">
                        <span class="text-muted">79.2 KB</span>
                      </li>
                      <li class="list-inline-item">
                        <span class="text-muted text-uppercase">psd</span>
                      </li>
                    </ul>
                  </div>

                  <div class="align-self-center ml-5">
                    <div class="dropdown">
                      <a
                        href="#"
                        class="btn btn-sm btn-ico btn-link text-muted w-auto"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        aria-expanded="false"
                      >
                        <i class="fe-more-vertical"></i>
                      </a>
                      <div class="dropdown-menu">
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Download <span class="ml-auto fe-download"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Share <span class="ml-auto fe-share-2"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Delete <span class="ml-auto fe-trash-2"></span>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <!-- File -->

              <!-- File -->
              <li class="list-group-item py-6">
                <div class="media">
                  <div class="icon-shape bg-primary text-white mr-5">
                    <i class="fe-paperclip"></i>
                  </div>

                  <div class="media-body align-self-center overflow-hidden">
                    <h6 class="text-truncate mb-0">
                      <a href="#" class="text-reset" title="E5419783-047D-4B4C-B30E-F24DD8247731.JPG"
                        >E5419783-047D-4B4C-B30E-F24DD8247731.JPG</a
                      >
                    </h6>

                    <ul class="list-inline small mb-0">
                      <li class="list-inline-item">
                        <span class="text-muted">79.2 KB</span>
                      </li>
                      <li class="list-inline-item">
                        <span class="text-muted text-uppercase">pdf</span>
                      </li>
                    </ul>
                  </div>

                  <div class="align-self-center ml-5">
                    <div class="dropdown">
                      <a
                        href="#"
                        class="btn btn-sm btn-ico btn-link text-muted w-auto"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        aria-expanded="false"
                      >
                        <i class="fe-more-vertical"></i>
                      </a>
                      <div class="dropdown-menu">
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Download <span class="ml-auto fe-download"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Share <span class="ml-auto fe-share-2"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Delete <span class="ml-auto fe-trash-2"></span>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <!-- File -->

              <!-- File -->
              <li class="list-group-item py-6">
                <div class="media">
                  <div class="icon-shape bg-primary text-white mr-5">
                    <i class="fe-paperclip"></i>
                  </div>

                  <div class="media-body align-self-center overflow-hidden">
                    <h6 class="text-truncate mb-0">
                      <a href="#" class="text-reset" title="E5419783-047D-4B4C-B30E-F24DD8247731.JPG"
                        >E5419783-047D-4B4C-B30E-F24DD8247731.JPG</a
                      >
                    </h6>

                    <ul class="list-inline small mb-0">
                      <li class="list-inline-item">
                        <span class="text-muted">79.2 KB</span>
                      </li>
                      <li class="list-inline-item">
                        <span class="text-muted text-uppercase">txt</span>
                      </li>
                    </ul>
                  </div>

                  <div class="align-self-center ml-5">
                    <div class="dropdown">
                      <a
                        href="#"
                        class="btn btn-sm btn-ico btn-link text-muted w-auto"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        aria-expanded="false"
                      >
                        <i class="fe-more-vertical"></i>
                      </a>
                      <div class="dropdown-menu">
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Download <span class="ml-auto fe-download"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Share <span class="ml-auto fe-share-2"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Delete <span class="ml-auto fe-trash-2"></span>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <!-- File -->

              <!-- File -->
              <li class="list-group-item py-6">
                <div class="media">
                  <div class="icon-shape bg-primary text-white mr-5">
                    <i class="fe-paperclip"></i>
                  </div>

                  <div class="media-body align-self-center overflow-hidden">
                    <h6 class="text-truncate mb-0">
                      <a href="#" class="text-reset" title="E5419783-047D-4B4C-B30E-F24DD8247731.JPG"
                        >E5419783-047D-4B4C-B30E-F24DD8247731.JPG</a
                      >
                    </h6>

                    <ul class="list-inline small mb-0">
                      <li class="list-inline-item">
                        <span class="text-muted">79.2 KB</span>
                      </li>
                      <li class="list-inline-item">
                        <span class="text-muted text-uppercase">pdf</span>
                      </li>
                    </ul>
                  </div>

                  <div class="align-self-center ml-5">
                    <div class="dropdown">
                      <a
                        href="#"
                        class="btn btn-sm btn-ico btn-link text-muted w-auto"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        aria-expanded="false"
                      >
                        <i class="fe-more-vertical"></i>
                      </a>
                      <div class="dropdown-menu">
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Download <span class="ml-auto fe-download"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Share <span class="ml-auto fe-share-2"></span>
                        </a>
                        <a class="dropdown-item d-flex align-items-center" href="#">
                          Delete <span class="ml-auto fe-trash-2"></span>
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <!-- File -->
            </ul>
          </div>
          <!-- Files -->
        </div>
      </div>
      <!-- Body -->
    </div>
  </div>
</template>
<script>
import avatarFemale from '@/assets/images/avatar_female.jpg';

export default {
  name: 'm-conversation-info',
  data() {
    return {
      avatarFemale,
    };
  },
};
</script>
