<template>
  <div>
    <div>
      <h1>ini adalah Default Layout</h1>
      <router-link to="/">Home</router-link><br />
      <router-link to="/user">User</router-link><br />
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "DefaultLayout",
};
</script>