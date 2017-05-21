<template>
<div class="content">
    <h1>Pro Zay</h1>
    <iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/324676193&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false">
    </iframe>
    <footer>
    Copyright (c) 2017 Copyright Holder All Rights Reserved.
</footer>
</div>

</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Permanent+Marker');

      h1 {
      padding: 10px 0 20px 0;
      margin: 0;
      font-family: 'Permanent Marker', cursive;
      text-align: center;
      color: #fff;
      font-size: 60px;
      text-shadow: 2px 2px 8px red;
      }
      .content{
        height: 100vh;
        width: 80%;
      }
      footer{
        margin-top: 10px;
        font-size: 10pt;
        color: red;
        text-align: center;
      }
</style>
