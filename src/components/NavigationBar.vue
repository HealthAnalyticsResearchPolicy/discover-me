<template>
  <div class="nav-bar">
    <b-navbar variant="primary">
      <b-navbar-brand
        href="#"
      >
        <img src="../assets/bannerAvenir.png" alt="Discover Me" height="66px"/>
      </b-navbar-brand>
      <b-navbar-nav
        class="ml-auto"
      >
        <b-button
          variant="secondary"
          size="lg"
        >
          Fork us on GitHub
          <b-icon
            icon="box-arrow-up-right"
          ></b-icon>
        </b-button>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script>
export default {
    name: 'NavigationBar'
}
</script>
