<template>
  <div>
    <b-navbar
      toggleable="lg"
      type="dark"
      fixed="top"
      sticky
      variant="dark"
    >
      <b-container>
        <b-navbar-brand>
          Adrian Gajos
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse" />

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <!-- <NuxtLink to="/" tag="b-nav-item">
              Home
            </NuxtLink> -->
            <b-nav-item href="#about" active>
              O mnie
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>

    <Nuxt />
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
}
</script>
