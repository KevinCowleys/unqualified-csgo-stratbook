<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="header">
    <input id="menu__toggle" type="checkbox" />
    <label class="menu__btn" for="menu__toggle">
      <span />
    </label>
    <div id="sideNav" class="sidenav menu__box">
      <div class="sideNav--contents">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/docs">Docs</RouterLink>
        <RouterLink to="/changelog">Changelog</RouterLink>
        <a href="https://github.com/Unqualified-CSGO/CSGO-Stratbook/releases">Download</a>
        <div class="sidebar-social">
          <!-- <span class="sr-only">Social:</span> -->
          <ul>
            <li>
              <a
                href="https://github.com/Unqualified-CSGO/CSGO-Stratbook"
                title="Unqualified CSGO Stratbook GitHub"
                class="no-mark-external"
                target="_blank"
              >
                <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <title>Unqualified CSGO Stratbook GitHub</title>
                  <path
                    d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"
                  />
                </svg>
                <!-- <span class="sr-only">GitHub</span> -->
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
header {
  display: grid;
}
.sidenav {
  display: flex;
  align-items: center;
  height: 100%;
  width: 250px;
  position: fixed;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
  transform-origin: 0% 0%;
  transform: translate(-100%, 0);
  transition: transform 0.5s cubic-bezier(0.77, 0.2, 0.05, 1);
  text-align: initial;
  z-index: 3;
}

.sideNav--contents {
  text-align: revert;
  width: 100%;
}

.sideNav--contents a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
  transition: 0.3s;
}

.sideNav--contents a:hover {
  color: #f1f1f1;
}

.sidebar-social {
  margin-top: 8px;
}

svg {
  fill: #818181;
  width: 20px;
}

svg:hover {
  fill: #f1f1f1;
}

ul,
ul > li > a {
  list-style-type: none; /* Remove bullets */
  padding: 0 !important; /* Remove padding */
  margin: 0; /* Remove margins */
}

ul {
  display: flex;
  justify-content: space-around;
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

@media screen and (max-height: 450px) {
  .sidenav {
    padding-top: 15px;
  }
  .sideNav--contents a {
    font-size: 18px;
  }
}
@media only screen and (min-width: 1500px) {
  .menu__btn {
    display: none !important;
  }
  .sidenav {
    transform: translate(0, 0);
  }
}
/* Code below is just to have it toggle nicely */
#menu__toggle {
  visibility: hidden;
}

#menu__toggle:checked ~ .menu__btn > span {
  transform: rotate(45deg);
}
#menu__toggle:checked ~ .menu__btn > span::before {
  top: 0;
  transform: rotate(0);
}
#menu__toggle:checked ~ .menu__btn > span::after {
  top: 0;
  transform: rotate(90deg);
}
#menu__toggle:checked ~ .menu__box {
  transform: translate(0, 0);
  left: 0;
}

.menu__btn {
  display: flex;
  align-items: center;
  position: fixed;
  top: 20px;
  left: 20px;
  width: 26px;
  height: 26px;
  cursor: pointer;
  z-index: 4;
}

.menu__btn > span,
.menu__btn > span::before,
.menu__btn > span::after {
  display: block;
  position: absolute;
  width: 100%;
  height: 2px;
  background-color: #616161;
  transition-duration: 0.25s;
}
.menu__btn > span::before {
  content: '';
  top: -8px;
}
.menu__btn > span::after {
  content: '';
  top: 8px;
}

.menu__box {
  box-shadow: 1px 0px 6px rgba(0, 0, 0, 0.2);
  transition-duration: 0.25s;
}
</style>
