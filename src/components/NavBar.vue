<template>
  <header class="header sticky top-0 bg-black-800 mb-5 opacity-75">
    <!-- <div class="h-2 w-full bg-primary-500"></div> -->
    <nav class="flex items-center justify-between flex-wrap py-6 container">
      <!-- site title / logo -->
      <div class="flex items-center flex-no-shrink mr-6">
        <strong>
          <h1 class="text-primary-500">JoshAFairhead</h1>
          <!-- bump me right a little bit! -->
        </strong>
      </div>
      <!-- end site title / logo -->

      <!-- mobile navigation toggle -->
      <div class="block sm:hidden">
        <button @click="toggle" class="nav-toggle">
          <svg
            class="fill-current h-3 w-3"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
      <!-- end navigation toggle -->

      <!-- Navigation Links-->
      <div
        :class="open ? 'block' : 'hidden'"
        class="w-full sm:flex sm:items-center sm:w-auto flex-grow sm:flex-grow-0"
      >
        <g-link class="nav-link" to="/">Home</g-link>
        <!-- <g-link class="nav-link" to="https://calendar.google.com/calendar/embed?src=vaq0no7iet9g02imla1gm4btaisepnmo%40import.calendar.google.com&ctz=Europe%2FBerlin">Calendar</g-link> -->
        <g-link class="nav-link" to="https://www.tothecosmos.org"
          >NOTABLOG</g-link
        >
        <!-- <g-link class="nav-link" to="/qualities/">Qualities</g-link> -->
        <!-- <g-link class="nav-link" to="/quantities/">Quantities</g-link> -->
      </div>
      <!-- End navigation Links-->
    </nav>
  </header>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
export default {
  data() {
    return {
      open: false,
    };
  },
  methods: {
    toggle() {
      this.open = !this.open;
    },
  },
};
</script>

<style lang="scss" scoped>
nav {
  .nav-toggle {
    @apply flex items-center px-3 py-2 text-primary-100;
    &:hover {
      @apply text-primary-500;
    }
  }
  .nav-link {
    display: block;
    @apply text-teal-500 uppercase py-3 text-right font-bold;
    @screen sm {
      @apply flex px-3 py-0 whitespace-no-wrap text-left;
    }
    &:hover,
    &:focus,
    &.active--exact {
      @apply text-teal-400;
    }
  }
}
</style>
