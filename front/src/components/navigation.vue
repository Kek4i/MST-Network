<template>
  <header>
    <a href="/" class="logo">MST Network</a>
    <nav>
      <div class="menu-links">
        <router-link to="/">Главная</router-link>
        <router-link to="/rules">Правила</router-link>
        <a href="https://vk.com/mstnetwork" target="_blank">Группа ВК</a>
        <a href="https://support.mstnw.net" target="_blank">Поддержка</a>
      </div>
    </nav>
    <div class="button-a">
      <button onclick="location.href='https://oauth.vk.com/authorize?client_id=6806434&amp;display=page&amp;response_type=code&amp;v=5.140&amp;scope=email&amp;redirect_uri=https://mstnw.net/oauth'">
        <i class="fa fa-vk" aria-hidden="true"></i> Авторизация</button>
    </div>
  </header>
</template>

<style scoped>

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1220px;
  margin-left: auto;
  margin-right: auto;
  font-family: "Mulish", sans-serif;
}

.logo{
  font-size: 36px;
  font-weight: bold;
  color: #6071ff;
  white-space: nowrap;
  padding-right: 25px;
}
a{
  text-decoration: none;
  color: black;
}

nav{
  width: 100%;
}

.menu-links {
  display: flex;
  justify-content: space-between;
  font-weight: 500;
}

.button-a{
  padding-left: 100px;
}

</style>

<script setup>

</script>