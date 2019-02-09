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
          >
            <span class="copy">Bild: Mikael Gustafsson</span>
          </div>
        </div>
      </section>
      <section class="grid-portfolio informationen">
        <div class="wrapper">
          <h1>Referenzen und Konzepte</h1>
          <ul class="grid">
            <li class="grid-item">
              <nuxt-link
                to="/eurovision-de"
                style="background-image: linear-gradient(to bottom, rgba(11,11,33,.25), rgba(11,11,33,.75)), url('https://apex.uwe-barthel.net/images/esc-artwork-2019.t48er45er2d.jpg')"
                class="img-portfolio"
              >
                <h2>Eurovision.de Konzept</h2>
              </nuxt-link>
            </li>
            <li class="grid-item">
              <nuxt-link
                to="/sv-hohenfichte"
                style="background-image: linear-gradient(to bottom, rgba(11,11,33,.25), rgba(11,11,33,.75)), url('https://apex.uwe-barthel.net/images/sv-hohenfichte-v2.15aweDAWs2551.jpg'); background-position: top;"
                class="img-portfolio"
              >
                <h2>Schützenverein Hohenfichte Webapp</h2>
              </nuxt-link>
            </li>
            <li class="grid-item">
              <nuxt-link
                to="/ib-barthel"
                style="background-image: linear-gradient(to bottom, rgba(11,11,33,.25), rgba(11,11,33,.75)), url('https://apex.uwe-barthel.net/images/ib-barthel.69ad15ad21Wed.png'); background-position: top;"
                class="img-portfolio"
              >
                <h2>Ingenieurbüro Barthel Website</h2>
              </nuxt-link>
            </li>
          </ul>
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