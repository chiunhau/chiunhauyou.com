<template lang="pug">
  .intro
    img.portrait(src='../assets/me.jpg')
    p.main Hi, <br/>I'm Chiunhau You. I'm a web developer based in Taipei, Taiwan. I make art with code.
    p.side I currently study in the Department of Commercial Design in Taiwan Tech (NTUST) and work as a front-end intern in 5xruby.<br/><br/>I love backpacking and couchsurfing so maybe I'll bump into you someday. But actually you can know me first by reading my CV :)
</template>

<script>
export default {
  name: 'about'
}
</script>

<style lang="scss">

$dark-gray: #333;
$gray: #bbb;
$light-gray: #ddd;

.intro {
  max-width: 1024px;
  margin: 0 auto;
  position: relative;

  p.main {
    width: 300px;
    text-align: left;
    font-size: 1.2em;
    font-weight: 700;
    line-height: 1.5em;
    color: #fff;
    position: absolute;
    top: 220px;
    left: 50px;
  }

  p.side {
    width: 280px;
    text-align: left;
    font-size: 1em;
    font-weight: 400;
    line-height: 1.3em;
    color: $light-gray;
    position: absolute;
    top: 255px;
    right: 50px;
  }
  .portrait {
    width: 100%;
    margin-top: 2rem;
  }
}

</style>
