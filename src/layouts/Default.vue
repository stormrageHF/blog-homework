<template>
  <div data-v-da896d1e class="layout">
    <header data-v-7e33895e="" class="header" :class="{ sticky: isSticky }">
      <div data-v-7e33895e="" class="container">
        <div data-v-7e33895e="" class="left">
          <g-link data-v-7e33895e="" to="/" class="home-link active"
            ><img
              data-v-7e33895e=""
              src="../assets/img/logo.332701b7.svg"
              alt="Nichlas W. Andersen"
              class="logo"
          /></g-link>
        </div>
        <nav data-v-7e33895e="" class="nav right">
          <g-link
            data-v-7e33895e=""
            to="/journal"
            aria-current="page"
            class="nav__link active--exact active"
            >Journal</g-link
          >
          <g-link data-v-7e33895e="" to="/contact" class="nav__link"
            >Say Hi!</g-link
          >
        </nav>
      </div>
    </header>

    <slot />

    <footer data-v-07acb5f8="" class="footer">
      <div data-v-07acb5f8="" class="container">
        <span data-v-07acb5f8="">Copyright © 2021</span>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  props:{
    isSticky: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<style>
</style>
