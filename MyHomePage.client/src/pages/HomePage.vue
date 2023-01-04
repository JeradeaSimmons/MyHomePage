<template>
<!--  
sports scores
local news
software news
quote?
back ground image
time
date
links to 
-linkedin
-github
-email
-->
<body>

  <div class="row m-3">
    <div class="col-md-3">
      <div class="bg-white" style="text-align:center;padding:1em 0;">> <iframe
          src="https://www.zeitverschiebung.net/clock-widget-iframe-v2?language=en&size=large&timezone=America%2FBoise&show=hour_minute"
          width="100%" height="140" frameborder="0" seamless></iframe> </div>
    </div>
  </div>
<!-- Possibly find different ones. Better fit for what I want. -->
  <div class="row">
    <iframe width="900" height="700" src="https://rss.app/embed/v1/imageboard/tIta2nNwsgtjjGup"
      frameborder="0"></iframe>
  </div>

  <div class="row">
    <iframe width="900" height="700" src="https://rss.app/embed/v1/imageboard/6Zz6HKydloq6WrqY"
      frameborder="0"></iframe>
  </div>

</body>







</template>
<script>
export default {
setup() {
  return {};
},
};
</script>
<style lang="scss" scoped>
body{
  background-image: url('https://source.unsplash.com/random/900×700/?nature');
  background-position: center;
  background-size: cover;
  min-height: 75em;
}

</style>