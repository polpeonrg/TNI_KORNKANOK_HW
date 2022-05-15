<template>
  <div id="app">
    <nav>
      <router-link class="link" :to="{ path: '/' }">Profile</router-link>
      <router-link class="link" :to="{ path: '/contact' }">Contact</router-link>
    </nav>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  text-align: left;
  color: #060a08;
}
body {
  margin: 0;
  background-color: #8da0a4;
}
section {
  margin: 0 30px;
}
nav {
  color: #b0bfc2;
  padding: 5px 0 0 0;
  background-color: #202723;
}
h1 {
  text-align: center;
}

div p,
a {
  color: #202723;
  font-size: 18px;
  margin: 10px 0 0 0;
}
a {
  text-decoration: none;
  display: inline-block;
}

.link {
  display: inline-block;
  padding: 10px;
  text-decoration: none;
  color: inherit;
}

.link:hover {
  color: #060a08;
  background-color: #5c7470;
  text-decoration: underline;
}
.router-link-exact-active {
  color: #060a08;
  background: #8da0a4;
}

.decorate {
  color: white;
  display: inline-block;
  margin: 0 10px 0 10px;
  width: 12px;
}
.decoration {
  position: relative;
  bottom: 10px;
  margin-bottom: 10px;
  display: block;
  text-align: center;
}
</style>
