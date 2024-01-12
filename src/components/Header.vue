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
                href="https://steamcommunity.com/id/D3ATHKeeper/"
                title="D3ATHKeeper Steam Profile"
                class="no-mark-external"
                target="_blank"
              >
                <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <title>D3ATHKeeper Steam Profile</title>
                  <path
                    d="M11.979 0C5.678 0 .511 4.86.022 11.037l6.432 2.658c.545-.371 1.203-.59 1.912-.59.063 0 .125.004.188.006l2.861-4.142V8.91c0-2.495 2.028-4.524 4.524-4.524 2.494 0 4.524 2.031 4.524 4.527s-2.03 4.525-4.524 4.525h-.105l-4.076 2.911c0 .052.004.105.004.159 0 1.875-1.515 3.396-3.39 3.396-1.635 0-3.016-1.173-3.331-2.727L.436 15.27C1.862 20.307 6.486 24 11.979 24c6.627 0 11.999-5.373 11.999-12S18.605 0 11.979 0zM7.54 18.21l-1.473-.61c.262.543.714.999 1.314 1.25 1.297.539 2.793-.076 3.332-1.375.263-.63.264-1.319.005-1.949s-.75-1.121-1.377-1.383c-.624-.26-1.29-.249-1.878-.03l1.523.63c.956.4 1.409 1.5 1.009 2.455-.397.957-1.497 1.41-2.454 1.012H7.54zm11.415-9.303c0-1.662-1.353-3.015-3.015-3.015-1.665 0-3.015 1.353-3.015 3.015 0 1.665 1.35 3.015 3.015 3.015 1.663 0 3.015-1.35 3.015-3.015zm-5.273-.005c0-1.252 1.013-2.266 2.265-2.266 1.249 0 2.266 1.014 2.266 2.266 0 1.251-1.017 2.265-2.266 2.265-1.253 0-2.265-1.014-2.265-2.265z"
                  />
                </svg>
                <!-- <span class="sr-only">Steam</span> -->
              </a>
            </li>
            <li>
              <a
                href="https://twitter.com/D3ATHKeeper"
                title="Unqualified CSGO Stratbook Twitter"
                class="no-mark-external"
                target="_blank"
              >
                <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <title>Unqualified CSGO Stratbook Twitter</title>
                  <path
                    d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"
                  />
                </svg>
                <!-- <span class="sr-only">Twitter</span> -->
              </a>
            </li>
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
