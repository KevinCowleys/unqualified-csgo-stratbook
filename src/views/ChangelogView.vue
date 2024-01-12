<script setup lang="ts">
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
</script>

<template>
  <div id="app">
    <Header />
    <div class="body-content">
      <div class="changelog">
        <div id="1.0.0" class="version">
          <span class="version--number">1.0.0</span>
          <span class="version--release-date">(15 July 2021)</span>
          <!-- <a href="#1.0.0" title="CSGO Stratbook version 1.0.0">copy</a> -->
          <div>
            <!-- <h3 class="version--header">General</h3> -->
            <ul>
              <li>Initial Release</li>
            </ul>
          </div>
        </div>
      </div>
      <Footer />
    </div>
  </div>
</template>

<style lang="scss">
.changelog {
  margin: 4rem 0;
  min-height: calc(80vh - 8rem);
}
.version {
  padding: 2rem;
}
.version--header {
  color: #66fcf1;
  font-size: 1.25rem;
}
.version--number {
  color: #66fcf1;
  font-size: 2rem;
  font-weight: 600;
  margin-right: 1rem;
}
</style>
