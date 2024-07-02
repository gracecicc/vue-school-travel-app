<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/brazil">Brazil</router-link>
    <router-link to="/panama">Panama</router-link>
    <router-link to="/hawaii">Hawaii</router-link>
    <router-link to="/jamaica">Jamaica</router-link>
  </div>
</template>
<script setup></script>

<style lang="css">
#nav .vue-school-active-link {
  border-bottom: 2px solid red;
  color: red;
}
</style>
