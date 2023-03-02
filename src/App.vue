<template>
  <div>
    <nav>
      <router-link to="/about">Data Binding =></router-link>
      |
      <router-link to="/databinding/string">Data String</router-link>
      |
      <router-link to="/databinding/html">Data Html</router-link>
      |
      <router-link to="/databinding/input">Data Input</router-link>
      |
      <router-link to="/databinding/select">Data Select</router-link>
      |
      <router-link to="/databinding/checkbox">Data Checkbox</router-link>
      |
      <router-link to="/databinding/radio">Data Radio</router-link>
      |
      <router-link to="/databinding/attribute">Data Attribute</router-link>
      |
      <router-link to="/databinding/list">Data List</router-link>
      |
      <router-link to="/databinding/class">Data Class</router-link>
      |
      <router-link to="/databinding/style">Data Style</router-link>
    </nav>
    <nav>
      <router-link to="/">Event =></router-link>
      |
      <router-link to="/event/click">Event Click</router-link>
      |
      <router-link to="/event/change">Event Change</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
