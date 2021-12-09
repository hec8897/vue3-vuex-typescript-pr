<template>
<div class="body">
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/phonebook">phonebook</router-link>
  </div>
  <router-view />
</div>
</template>

<style lang="scss">
@import "@/assets/elements.scss";

*{
  margin: 0;
  padding: 0;
}
div.body{
  padding: 50px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

</style>
