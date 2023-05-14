<template>
  <router-link to="/users">ir a los usuarios</router-link>
  <h2 id="homee">Estamos en la HOME</h2>
</template>

<script>
export default {
  name: "HomeView",
  props: {
    msg: String,
  },
};
</script>
