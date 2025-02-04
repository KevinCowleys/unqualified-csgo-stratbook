<template>
  <div class="footer">
    <img src="/logo.png" alt="Unqualified CSGO Stratbook logo" />
    <div>
      <a
        href="https://github.com/Unqualified-CSGO/CSGO-Stratbook"
        target="_blank"
        class="links"
        >Github</a
      >
    </div>
    <div class="made-by">
      Made by Kevin Cowley
    </div>
  </div>
</template>

<style scoped>
.footer {
  background-color: #232327;
  height: 250px;
  text-align: center;
}
.footer .links {
  color: white;
  display: inline-block;
  margin: 10px;
  transition: 0.5s;
}
.footer .links:hover {
  color: #66fcf1;
}
.made-by {
  font-size: 0.8em;
}
</style>
