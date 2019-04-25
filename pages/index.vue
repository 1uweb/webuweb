<template>
  <div class="page">
    <navigation/>
    <main id="app-root">
      <section class="app-hero">
        <div
          class="app-plane"
          style="background-image: linear-gradient(to bottom, rgba(11,11,33,.75), rgba(11,11,33,1)), url('https://apex.uwe-barthel.net/images/pawel-czerwinski-1311900-unsplash.Oip88jj089.jpg')"
        ></div>
        <div class="wrapper">
          <div
            class="app-bg-frontpage"
            style="background-image: url('https://apex.uwe-barthel.net/images/pawel-czerwinski-1311900-unsplash.Oip88jj089.jpg')"
          >
            <span class="copy">Pawel Czerwinski</span>
          </div>
        </div>
      </section>
      <section class="grid-portfolio informationen">
        <div class="wrapper">
          <h1>Referenzen und Konzepte</h1>
          <ul class="grid">
            <li class="grid-item">
              <nuxt-link
                to="#"
                style="background-image: linear-gradient(to bottom, rgba(11,11,33,.25), rgba(11,11,33,.75)), url('https://apex.uwe-barthel.net/images/esc-artwork-2019.t48er45er2d.jpg')"
                class="img-portfolio"
              >
                <h2>Eurovision.de Konzept (soon)</h2>
              </nuxt-link>
            </li>
            <li class="grid-item">
              <a
                href="https://sv-hohenfichte.de"
                target="_blank"
                style="background-image: linear-gradient(to bottom, rgba(11,11,33,.25), rgba(11,11,33,.75)), url('https://apex.uwe-barthel.net/images/sv-hohenfichte-v2.15aweDAWs2551.jpg'); background-position: top;"
                class="img-portfolio"
              >
                <h2>Schützenverein Hohenfichte Webapp</h2>
              </a>
            </li>
            <li class="grid-item">
              <a
                href="https://ingenieurbuero-barthel.de"
                style="background-image: linear-gradient(to bottom, rgba(11,11,33,.25), rgba(11,11,33,.75)), url('https://apex.uwe-barthel.net/images/ib-barthel.69ad15ad21Wed.png'); background-position: top;"
                class="img-portfolio"
              >
                <h2>Ingenieurbüro Barthel Website</h2>
              </a>
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
