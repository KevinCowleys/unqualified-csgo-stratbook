<script setup lang="ts">
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
</script>

<template>
  <div id="app">
    <Header />
    <div class="body-content">
      <div class="main">
        <div class="background-image">
          <img src="/home.jpg" alt="Image of the home view" />
        </div>
        <h3 class="title">Unqualified CSGO Stratbook</h3>
        <div class="section-1">
          <div class="section-1--content">
            <h3>Are you ready to step up your game?</h3>
            <p>
              The Unqualified CSGO Stratbook is an app where you can note down your utility lineups
              and strats to help your team improve.
            </p>
            <a href="#more" class="findOutMore">FIND OUT MORE</a>
            <a href="https://github.com/Unqualified-CSGO/CSGO-Stratbook/releases" class="download"
              >GET IT NOW</a
            >
          </div>
          <div class="section-1--content-desktop">
            <img
              src="/desktop.png"
              alt="Image of Counter-Strike: Global Offensive"
              title="Counter-Strike: Global Offensive Stratbook"
            />
          </div>
        </div>
        <div id="more" class="section-2">
          <div class="section-2--content">
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-pencil-square"
                viewBox="0 0 16 16"
              >
                <path
                  d="M15.502 1.94a.5.5 0 0 1 0 .706L14.459 3.69l-2-2L13.502.646a.5.5 0 0 1 .707 0l1.293 1.293zm-1.75 2.456-2-2L4.939 9.21a.5.5 0 0 0-.121.196l-.805 2.414a.25.25 0 0 0 .316.316l2.414-.805a.5.5 0 0 0 .196-.12l6.813-6.814z"
                />
                <path
                  fill-rule="evenodd"
                  d="M1 13.5A1.5 1.5 0 0 0 2.5 15h11a1.5 1.5 0 0 0 1.5-1.5v-6a.5.5 0 0 0-1 0v6a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-11a.5.5 0 0 1 .5-.5H9a.5.5 0 0 0 0-1H2.5A1.5 1.5 0 0 0 1 2.5v11z"
                />
              </svg>
              <h3>EASY TO EDIT</h3>
            </div>
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-palette-fill"
                viewBox="0 0 16 16"
              >
                <path
                  d="M12.433 10.07C14.133 10.585 16 11.15 16 8a8 8 0 1 0-8 8c1.996 0 1.826-1.504 1.649-3.08-.124-1.101-.252-2.237.351-2.92.465-.527 1.42-.237 2.433.07zM8 5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm4.5 3a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zM5 6.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm.5 6.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3z"
                />
              </svg>
              <h3>CREATE YOUR OWN THEME</h3>
            </div>
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-speedometer"
                viewBox="0 0 16 16"
              >
                <path
                  d="M8 2a.5.5 0 0 1 .5.5V4a.5.5 0 0 1-1 0V2.5A.5.5 0 0 1 8 2zM3.732 3.732a.5.5 0 0 1 .707 0l.915.914a.5.5 0 1 1-.708.708l-.914-.915a.5.5 0 0 1 0-.707zM2 8a.5.5 0 0 1 .5-.5h1.586a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8zm9.5 0a.5.5 0 0 1 .5-.5h1.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5zm.754-4.246a.389.389 0 0 0-.527-.02L7.547 7.31A.91.91 0 1 0 8.85 8.569l3.434-4.297a.389.389 0 0 0-.029-.518z"
                />
                <path
                  fill-rule="evenodd"
                  d="M6.664 15.889A8 8 0 1 1 9.336.11a8 8 0 0 1-2.672 15.78zm-4.665-4.283A11.945 11.945 0 0 1 8 10c2.186 0 4.236.585 6.001 1.606a7 7 0 1 0-12.002 0z"
                />
              </svg>
              <h3>FAST & LOCAL</h3>
            </div>
            <div>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-phone-fill"
                viewBox="0 0 16 16"
              >
                <path
                  d="M3 2a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V2zm6 11a1 1 0 1 0-2 0 1 1 0 0 0 2 0z"
                />
              </svg>
              <h3>MOBILE FRIENDLY</h3>
            </div>
          </div>
        </div>
      </div>
      <div class="light">
        <div class="section-3">
          <div class="section-3--content-mobile">
            <img src="/strat.png" alt="Image of strat view" title="CSGO Strats" />
          </div>
          <div class="section-3--content">
            <h3>
              NO MORE EXCUSES.
              <br />
              BE SERIOUS NOW.
            </h3>
            <p>
              A lot of startup teams always struggle with strats, utility and the basics. Start by
              creating proper strats and util for your team today.
            </p>
          </div>
        </div>
      </div>
      <div>
        <div class="section-4">
          <div class="section-4--content">
            <h3>CREATE YOUR THEME</h3>
            <p>
              The program was designed from the ground up to allow you, the player, to customise it
              to your taste. Create what fits you and your team.
            </p>
          </div>
          <div class="section-4--content-desktop">
            <img
              src="/settings-top.png"
              alt="Image of the top of the settings view"
              title="CSGO Settings"
            />
          </div>
        </div>
      </div>
      <Footer />
    </div>
  </div>
</template>

<style lang="scss">
h3.title {
  color: white;
  margin: auto;
  font-size: 2rem;
  padding: 4rem 0;
  position: relative;
  text-align: center;
  z-index: 1;
}
.main {
  height: auto;
  position: relative;
}
.background-image {
  background: no-repeat center center fixed;
  background-size: cover;
  display: block;
  left: -5px;
  top: -5px;
  bottom: -5px;
  position: absolute;
  right: -5px;
  z-index: 0;
  -webkit-filter: blur(5px) grayscale(70%);
  -moz-filter: blur(5px) grayscale(70%);
  -o-filter: blur(5px) grayscale(70%);
  -ms-filter: blur(5px) grayscale(70%);
  filter: blur(5px) grayscale(70%);
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  margin: -1.5rem;
  overflow: hidden;
}
.background-image img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}
.section-1,
.section-2,
.section-3,
.section-4 {
  align-items: center;
  color: white;
  display: flex;
  justify-content: space-evenly;
  padding: 4rem 1rem;
  margin: auto;
  position: relative;
  flex-wrap: wrap;
  z-index: 1;
}
.section-3 img,
.section-4 img {
  width: 100%;
}
.light {
  background-color: #232327;
}
.section-1 h3 {
  font-size: 40px;
}
.section-1--content {
  width: 25rem;
}
.section-1--content,
.section-2--content {
  text-align: center;
}
.section-1--content-desktop {
  margin-top: 5rem;
}
.section-1--content-desktop img {
  width: 100%;
}
.section-1--content a {
  border-radius: 50px;
  color: #0b0c10;
  text-decoration: none;
  padding: 15px;
  font-weight: 300;
  width: 130px;
  display: inline-block;
  text-align: center;
}
.section-1--content a.findOutMore {
  background-color: #c5c6c7;
}
.section-1--content a.download {
  background-color: #66fcf1;
}
.section-1 a {
  margin: 1rem auto;
}
.section-1--content a:hover {
  opacity: 0.75;
}
.section-2--content {
  display: flex;
  flex-wrap: wrap;
  padding: 7rem 1rem 12rem 1rem;
  width: 100%;
}
.section-2--content div {
  width: 50%;
  padding-bottom: 2rem;
}
.section-2--content svg {
  width: 70px;
  height: 70px;
  fill: white;
}
.section-1--content-desktop img,
.section-3--content-mobile img,
.section-4--content-desktop img {
  box-shadow: 0 0 6px #45a59e;
}
@media only screen and (min-width: 576px) {
  h3.title,
  .section-1,
  .section-2,
  .section-3,
  .section-4 {
    max-width: 576px;
  }
}
@media only screen and (min-width: 768px) {
  .section-2--content div {
    width: calc(100% / 4);
  }
}
@media only screen and (min-width: 992px) {
  .main {
    height: 70rem;
  }
  h3.title,
  .section-1,
  .section-2,
  .section-3,
  .section-4 {
    max-width: 992px;
  }
  .section-3,
  .section-4 {
    /* flex-wrap: nowrap; */
    padding-top: 7rem;
    padding-bottom: 7rem;
  }
  .section-1--content {
    padding-right: 8rem;
    text-align: inherit;
  }
  /* .section-2--content, */
  .section-3--content,
  .section-4--content {
    width: 50%;
    padding: 0 2rem;
  }
  .section-1--content-desktop,
  .section-4--content-desktop {
    width: 25rem;
    padding-left: 2rem;
  }
  .section-3--content-mobile {
    width: 25rem;
  }
  .section-1 img,
  .section-4 img {
    width: auto;
    max-width: none;
    height: 400px;
  }
  .section-1--content a.download {
    margin-left: 20px;
  }
}
@media only screen and (min-width: 1200px) {
  h3.title,
  .section-1,
  .section-2,
  .section-3,
  .section-4 {
    max-width: 1200px;
  }
}
</style>
