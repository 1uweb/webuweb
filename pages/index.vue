<template>
  <div class="page">
    <navigation/>
    <main id="app-root">
      <section class="app-hero">
        <div
          class="app-plane"
          style="background-image: linear-gradient(to bottom, rgba(11,11,33,.75), rgba(11,11,33,1)), url('https://apex.uwe-barthel.net/images/wallpaper_mikael_gustafsson.54adfa15611.png')"
        ></div>
        <div class="wrapper">
          <div
            class="app-bg-frontpage"
            style="background-image: url('https://apex.uwe-barthel.net/images/wallpaper_mikael_gustafsson.54adfa15611.png')"
          ></div>
        </div>
      </section>
    </main>
    <sitemap/>
  </div>
</template>

<script>
import Navigation from "@/components/Navigation";
import Sitemap from "@/components/Sitemap";

export default {
  head: {
    title: "Uwe Barthel"
  },
  components: {
    Navigation,
    Sitemap
  }
};
</script>