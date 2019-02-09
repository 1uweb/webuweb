<template>
  <div class="page">
    <navigation/>
    <main id="app-root">
      <section class="app-hero">
        <div class="app-plane"></div>
        <div
          class="app-bg-frontpage wrapper"
          style="background-image: url('https://apex.uwe-barthel.net/images/esc-artwork-2019.t48er45er2d.jpg')"
        ></div>
      </section>
    </main>
  </div>
</template>

<script>
import Navigation from "@/components/Navigation";

export default {
  head: {
    title: "Uwe Barthel"
  },
  components: {
    Navigation
  }
};
</script>