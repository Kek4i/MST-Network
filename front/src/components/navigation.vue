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
header{
  max-width: 1220px;
  display: flex;
  box-shadow: 0px 4px 10px 0 rgba(0, 0, 0, 0.05);
  margin-right: auto;
  margin-left: auto;
}

a{
  text-decoration: none;
}

nav{
  width: 100vw;
  height: 70px;
  background: transparent;
}

.logo{
  font-size: 36px;
  font-weight: bold;
  color: #6071ff;
  white-space: nowrap;
  padding-right: 25px;
}

.menu-links{
  flex-grow: 1;
  justify-content: space-between;
  align-items: stretch;
  text-align: center;
}

.fa-vk:before{
  content: "\f189";
}

button{
  cursor: pointer;
  width: 160px;
  height: 36px;
  border-radius: 5px;
  background-color: #6071ff;
  color: #ffffff;
  font-weight: 600;
  border: none;
}
</style>

<script setup>

</script>