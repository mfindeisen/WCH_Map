<template>
  <v-toolbar color="yellow">
    <!-- <v-app-bar-nav-icon></v-app-bar-nav-icon> -->
    <v-toolbar-title>
      <h1 class="toolbar-title"><a href="https://workingclasshistory.com">WORKING CLASS HISTORY</a></h1>
      <nav id="site-navigation" class="main-navigation" role="navigation">
        <div class="menu-header-menu-wch-container">
            <!-- //HC -->
          <ul id="top-menu" class="menu nav-menu" aria-expanded="false">
            <li
              id="menu-item-20"
              class="
                menu-item
                menu-item-type-post_type
                menu-item-object-page menu-item-21
              "
            >
              <a target="_blank" href="https://workingclasshistory.com/about/"
                >About</a
              >
            </li>
            <li
              id="menu-item-21"
              class="
                menu-item
                menu-item-type-post_type
                menu-item-object-page menu-item-21
              "
            >
              <a target="_blank" href="https://stories.workingclasshistory.com/"
                >Stories</a
              >
            </li>
            <li
              id="menu-item-152"
              class="
                menu-item
                menu-item-type-post_type
                menu-item-object-page menu-item-152
              "
            >
              <a target="_blank" href="https://workingclasshistory.com/podcast/"
                >Podcast</a
              >
            </li>
            <li
              id="menu-item-20"
              class="
                menu-item
                menu-item-type-post_type
                menu-item-object-page menu-item-20
              "
            >
              <a target="_blank" href="https://workingclasshistory.com/sign-up/"
                >Sign up</a
              >
            </li>
            <li
              id="menu-item-18"
              class="
                menu-item
                menu-item-type-post_type
                menu-item-object-page menu-item-18
              "
            >
              <a target="_blank" href="https://workingclasshistory.com/support/"
                >Support us</a
              >
            </li>
            <li
              id="menu-item-95"
              class="
                menu-item
                menu-item-type-custom
                menu-item-object-custom
                menu-item-95
              "
            >
              <a target="_blank" href="https://shop.workingclasshistory.com/"
                >Shop</a
              >
            </li>
            <li
              id="menu-item-96"
              class="
                menu-item
                menu-item-type-custom
                menu-item-object-custom
                menu-item-95
              "
            >
              <a target="_blank" href="https://workingclasshistory.com/"
                >Home</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </v-toolbar-title>
  </v-toolbar>
</template>

<script>
export default {
  name: "MainTopBar",
};
</script>

<style>
.toolbar-title a{
    text-decoration: none;
    color: black !important;
}
</style>