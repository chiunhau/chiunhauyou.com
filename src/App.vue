<template lang="pug">
  #app
    h1.title CHIUNHAU YOU
    .nav
      ul
        li
          router-link(to='about') ABOUT
        li
          router-link(to='projects') PROJECTS
        li
          router-link(to='cv') CV
        li
          router-link(to='contacts') CONTACTS
    router-view
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Raleway:500,600,700,900');
@import 'assets/normalize.css';

$dark-gray: #333;
$gray: #bbb;
$light-gray: #ddd;


#app {
  font-family: 'Raleway', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

h1.title {
  font-weight: 900;
  font-size: 2.25em;
  letter-spacing: 0.13em;
  margin-top: 1em;
  margin-bottom: 0.4em;
}

.nav ul {
  margin: 0;
  padding: 0;
  list-style: none;

  li {
    display: inline;
    margin: 0;
    padding-left: 0.95rem;
    padding-right: 0.9rem;

    a {
      color: $dark-gray;
      text-decoration: none;
    }
  }
}
</style>
