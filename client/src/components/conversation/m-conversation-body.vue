<template>
  <div class="chat-body">
    <!-- Chat: Header -->
    <m-conversation-header />
    <!-- Chat: Header -->

    <!-- Chat: Search -->
    <m-conversation-search />
    <!-- Chat: Search -->

    <!-- Chat: Content-->
    <div class="chat-content px-lg-8">
      <div class="container-xxl py-6 py-lg-10">
        <!-- Message -->
        <div class="message">
          <!-- Avatar -->
          <a class="avatar avatar-sm mr-4 mr-lg-5" href="#" data-chat-sidebar-toggle="#chat-2-info">
            <img class="avatar-img" :src="avatarFemale" alt="" />
          </a>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center">
                <!-- Message: content -->
                <div class="message-content bg-light">
                  <h6 class="mb-2">Anna Bridges</h6>
                  <div>
                    Yeah, I'm going to meet a friend of mine at the department store. I have to buy some presents for my
                    parents.
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->

                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 ml-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: Body -->
        </div>
        <!-- Message -->

        <!-- Message -->
        <div class="message message-right">
          <!-- Avatar -->
          <div class="avatar avatar-sm ml-4 ml-lg-5 d-none d-lg-block">
            <img class="avatar-img" :src="avatarMale" alt="" />
          </div>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center justify-content-end">
                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 mr-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->

                <!-- Message: content -->
                <div class="message-content bg-primary text-white">
                  <div>
                    Yeah, I'm going to meet a friend of mine at the department store. I have to buy some presents for my
                    parents.
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->
              </div>
            </div>
            <!-- Message: row -->

            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center justify-content-end">
                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 mr-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->

                <!-- Message: content -->
                <div class="message-content bg-primary text-white">
                  <div class="media">
                    <a href="#" class="icon-shape mr-5">
                      <i class="fe-paperclip"></i>
                    </a>
                    <div class="media-body overflow-hidden flex-fill">
                      <a href="#" class="d-block text-truncate font-medium text-reset">bootstrap.min.js</a>
                      <ul class="list-inline small mb-0">
                        <li class="list-inline-item">
                          <span class="t">79.2 KB</span>
                        </li>
                        <li class="list-inline-item">
                          <span class="text-uppercase">js</span>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
                <!-- Message: content -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: body -->
        </div>
        <!-- Message -->

        <!-- Divider -->
        <m-message-divider text="Today" />
        <!-- Divider -->

        <!-- Message -->
        <div class="message">
          <!-- Avatar -->
          <a class="avatar avatar-sm mr-4 mr-lg-5" href="#" data-chat-sidebar-toggle="#chat-2-info">
            <img class="avatar-img" :src="avatarFemale" alt="" />
          </a>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center">
                <!-- Message: content -->
                <div class="message-content bg-light w-100">
                  <h6 class="mb-2">Anna Bridges shared 3 photos:</h6>
                  <div class="form-row py-3">
                    <div class="col">
                      <img
                        class="img-fluid rounded"
                        src="https://themes.2the.me/Boomerang/1.2/assets/images/team/1.jpg"
                        data-action="zoom"
                        alt=""
                      />
                    </div>
                    <div class="col">
                      <img
                        class="img-fluid rounded"
                        src="https://themes.2the.me/Boomerang/1.2/assets/images/team/2.jpg"
                        data-action="zoom"
                        alt=""
                      />
                    </div>
                    <div class="col">
                      <img
                        class="img-fluid rounded"
                        src="https://themes.2the.me/Boomerang/1.2/assets/images/team/3.jpg"
                        data-action="zoom"
                        alt=""
                      />
                    </div>
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->

                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 ml-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->
              </div>
            </div>
            <!-- Message: row -->

            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center">
                <!-- Message: content -->
                <div class="message-content bg-light">
                  <div>
                    Yeah, I'm going to meet a friend of mine at the department store. I have to buy some presents for my
                    parents.
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->

                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 ml-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: body -->
        </div>
        <!-- Message -->

        <!-- Message -->
        <div class="message message-right">
          <!-- Avatar -->
          <div class="avatar avatar-sm ml-4 ml-lg-5 d-none d-lg-block">
            <img class="avatar-img" :src="avatarMale" alt="" />
          </div>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center justify-content-end">
                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 mr-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->

                <!-- Message: content -->
                <div class="message-content bg-primary text-white">
                  <div>
                    I'm going to meet a friend of mine at the department store. Yeah, I have to buy some presents for my
                    parents.
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: body -->
        </div>
        <!-- Message -->

        <!-- Message -->
        <div class="message">
          <!-- Avatar -->
          <a class="avatar avatar-sm mr-4 mr-lg-5" href="#" data-chat-sidebar-toggle="#chat-2-info">
            <img class="avatar-img" :src="avatarFemale" alt="" />
          </a>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center">
                <!-- Message: content -->
                <div class="message-content bg-light">
                  <h6 class="mb-2">Anna Bridges</h6>
                  <div>
                    I'm going to meet a friend of mine at the department store. Yeah, I have to buy some presents for my
                    parents.
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->

                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 ml-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: body -->
        </div>
        <!-- Message -->

        <!-- Message -->
        <div class="message message-right">
          <!-- Avatar -->
          <div class="avatar avatar-sm ml-4 ml-lg-5 d-none d-lg-block">
            <img class="avatar-img" :src="avatarMale" alt="" />
          </div>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center justify-content-end">
                <!-- Message: dropdown -->
                <div class="dropdown">
                  <a
                    class="text-muted opacity-60 mr-3"
                    href="#"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                  >
                    <i class="fe-more-vertical"></i>
                  </a>

                  <div class="dropdown-menu">
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Edit <span class="ml-auto fe-edit-3"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Share <span class="ml-auto fe-share-2"></span>
                    </a>
                    <a class="dropdown-item d-flex align-items-center" href="#">
                      Delete <span class="ml-auto fe-trash-2"></span>
                    </a>
                  </div>
                </div>
                <!-- Message: dropdown -->

                <!-- Message: content -->
                <div class="message-content bg-primary text-white">
                  <div>
                    Yeah, I'm going to meet a friend of mine at the department store. I have to buy some presents for my
                    parents.
                  </div>

                  <div class="mt-1">
                    <small class="opacity-65">8 mins ago</small>
                  </div>
                </div>
                <!-- Message: content -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: body -->
        </div>
        <!-- Message -->

        <!-- Message: Typing -->
        <div class="message">
          <!-- Avatar -->
          <a class="avatar avatar-sm mr-4 mr-lg-5" href="#" data-chat-sidebar-toggle="#chat-2-info">
            <img class="avatar-img" :src="avatarFemale" alt="" />
          </a>

          <!-- Message: body -->
          <div class="message-body">
            <!-- Message: row -->
            <div class="message-row">
              <div class="d-flex align-items-center">
                <!-- Message: content -->
                <div class="message-content bg-light">
                  <div>
                    Anna is typing<span class="typing-dots"><span>.</span><span>.</span><span>.</span></span>
                  </div>
                </div>
                <!-- Message: content -->
              </div>
            </div>
            <!-- Message: row -->
          </div>
          <!-- Message: body -->
        </div>
        <!-- Message: Typing -->
      </div>

      <!-- Scroll to end -->
      <div class="end-of-chat"></div>
    </div>
    <!-- Chat: Content -->

    <!-- Chat: DropzoneJS container -->
    <div class="chat-files hide-scrollbar px-lg-8">
      <div class="container-xxl">
        <div class="dropzone-previews-js form-row py-4"></div>
      </div>
    </div>
    <!-- Chat: DropzoneJS container -->

    <!-- Chat: Footer -->
    <m-conversation-footer />
    <!-- Chat: Footer -->
  </div>
</template>

<script>
import MConversationFooter from '@/components/conversation/m-conversation-footer';
import MMessageDivider from '@/components/conversation/m-message-divider';
import avatarMale from '@/assets/images/avatar_male.jpg';
import avatarFemale from '@/assets/images/avatar_female.jpg';
import MConversationHeader from '@/components/conversation/m-conversation-header';
import MConversationSearch from '@/components/conversation/m-conversation-search';

export default {
  name: 'm-conversation-body',
  components: { MConversationSearch, MConversationHeader, MConversationFooter, MMessageDivider },
  data() {
    return {
      avatarMale,
      avatarFemale,
    };
  },
};
</script>
