<template>
  <div class="navigation navbar navbar-light justify-content-center py-xl-7">
    <!-- Brand -->
    <a href="#" class="d-none d-xl-block mb-6">
      <m-logo />
    </a>

    <!-- Menu -->
    <ul
      class="
        nav
        navbar-nav
        flex-row flex-xl-column flex-grow-1
        justify-content-between justify-content-xl-center
        py-3 py-lg-0
      "
      role="tablist"
    >
      <!-- Invisible item to center nav vertically -->
      <li class="nav-item d-none d-xl-block invisible flex-xl-grow-1">
        <a class="nav-link position-relative p-0 py-xl-3" href="#" title="">
          <i class="icon-lg fe-x"></i>
        </a>
      </li>

      <!-- Create group -->
      <li class="nav-item">
        <a
          @click.prevent="changeTab(tabs.CREATE_CONVERSATION)"
          :class="{ active: isTabActive(tabs.CREATE_CONVERSATION) }"
          class="nav-link position-relative p-0 py-xl-3"
          data-toggle="tab"
          href="#tab-content-create-chat"
          title="Create chat"
          role="tab"
        >
          <i class="icon-lg fe-edit"></i>
        </a>
      </li>

      <!-- Friend -->
      <li class="nav-item mt-xl-9">
        <a
          @click.prevent="changeTab(tabs.FRIENDS_LIST)"
          :class="{ active: isTabActive(tabs.FRIENDS_LIST) }"
          class="nav-link position-relative p-0 py-xl-3"
          data-toggle="tab"
          href="#tab-content-friends"
          title="Friends"
          role="tab"
        >
          <i class="icon-lg fe-users"></i>
        </a>
      </li>

      <!-- Chats -->
      <li class="nav-item mt-xl-9">
        <a
          @click.prevent="changeTab(tabs.CONVERSATIONS)"
          :class="{ active: isTabActive(tabs.CONVERSATIONS) }"
          class="nav-link position-relative p-0 py-xl-3"
          data-toggle="tab"
          href="#tab-content-dialogs"
          title="Chats"
          role="tab"
        >
          <i class="icon-lg fe-message-square"></i>
          <div class="badge badge-dot badge-primary badge-bottom-center"></div>
        </a>
      </li>

      <!-- Profile -->
      <li class="nav-item mt-xl-9 flex-xl-grow-1">
        <a
          @click.prevent="changeTab(tabs.PROFILE)"
          :class="{ active: isTabActive(tabs.PROFILE) }"
          class="nav-link position-relative p-0 py-xl-3"
          data-toggle="tab"
          href="#tab-content-user"
          title="User"
          role="tab"
        >
          <i class="icon-lg fe-user"></i>
        </a>
      </li>

      <!-- Settings -->
      <li class="nav-item mt-xl-9">
        <a class="nav-link position-relative p-0 py-xl-3" href="settings.html" title="Settings">
          <i class="icon-lg fe-settings"></i>
        </a>
      </li>
    </ul>
    <!-- /Menu -->
  </div>
</template>

<script>
import { mapActions, mapState } from 'vuex';
import { TABS } from '@/constants';
import MLogo from '@/components/icons/m-logo';

export default {
  name: 'm-navigation',
  components: { MLogo },
  data() {
    return {
      tabs: TABS,
    };
  },
  computed: {
    ...mapState('sidebar', ['currentTab']),
  },
  methods: {
    ...mapActions('sidebar', ['CHANGE_TAB']),
    changeTab(tab) {
      if (tab === this.currentTab) {
        return;
      }

      this.CHANGE_TAB(tab);
    },
    isTabActive(tabName) {
      return tabName === this.currentTab;
    },
  },
};
</script>
