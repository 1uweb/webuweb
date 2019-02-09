<template>
  <div class="page">
    <navigation/>
    <main id="app-root">
      <section class="page-hero">
        <div
          class="app-plane"
          style="background-image: linear-gradient(to bottom, rgba(11,11,33,.75), rgba(11,11,33,1)), url('https://apex.uwe-barthel.net/images/city-artwork.6e390e17b9da69d4c28ce24a8164ffc1.jpg')"
        ></div>
        <div class="wrapper">
          <div
            class="app-bg-frontpage wrapper"
            style="background-image: url('https://apex.uwe-barthel.net/images/city-artwork.6e390e17b9da69d4c28ce24a8164ffc1.jpg')"
          ></div>
        </div>
        <span class="bar-wrapper--big">
          <span class="bar--big-whitespace">
            <span class="bar--big-line"></span>
          </span>
        </span>
      </section>
      <section class="wrapper informationen">
        <h1>Zu meiner Person</h1>
        <p>
          Hi, ich bin Uwe und komme aus den schönen Augustusburg im Vorerzgebirge. In diesem Abschnitt meiner Website möchte ich mich ihnen Vorstellen, damit man einen bessern Eindruck von meiner Person bekommt.
          Als ich ein zweiwöchiges, schulisches Praktikum bei einer Agentur machte, fiel mir auf, dass mein späterer Beruf einmal Informatiker werden soll. Nach diesem Praktikum begann ich damit Webseiten in HTML & CSS zu schreiben. Daraus ist dann ein Hobby und schlussendlich auch eine Leidenschaft entstanden. Aktuell lerne ich die Programmiersprachen JavaScript - einschließlich React - und PhP. Mein derzeitiger Editor ist VSCode von Microsoft.
        </p>
        <h1>Meine Erfahrung</h1>
        <ul class="erfahrung">
          <li>
            <i class="fab fa-youtube"></i> 4,5 Jahre YouTube Erfahrung
          </li>
          <li>
            <i class="fas fa-code"></i> 1,5 Jahre Webdesign Erfahrung
          </li>
          <li>
            <i class="fab fa-vuejs"></i> 1 Monat Nuxt.js Erfahrung
          </li>
          <li>
            <i class="fab fa-react"></i> 4,5 Monate Next.js Erfahrung
          </li>
        </ul>
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
    title: "Über - Uwe Barthel"
  },
  components: {
    Navigation,
    Sitemap
  }
};
</script>