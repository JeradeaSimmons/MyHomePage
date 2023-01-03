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
        <div class="bg-white" style="text-align:center;padding:1em 0;">> <iframe src="https://www.zeitverschiebung.net/clock-widget-iframe-v2?language=en&size=large&timezone=America%2FBoise&show=hour_minute" width="100%" height="140" frameborder="0" seamless></iframe> </div>
      </div>
      <div class="col-md-5">
        
      </div>
    </div>
    <div class="row text-white text-center">
   </div>
    <div class="row text-white d-flex justify-content-evenly">
      <div class="col-md-3">LOCAL/WORLD NEWS</div>
      <div class="col-md-3">TECH NEWS</div>
      <div class="col-md-3">
        <iframe align="center"
          src="//widget.calendarlabs.com/v1/quot.php?cid=101&ver=1.2&uid=9442536361&c=random&l=en&cbg=FFFFFF&cb=1&cbc=000000&cf=calibri&cfg=000000&qfs=bi&qta=center&tfg=000000&tfs=bi&afc=000000&afs=i"
          width="300" height="210" marginwidth=0 marginheight=0 frameborder=0 scrolling=no
          allowtransparency='true'>Loading...</iframe>
        <div align="center" style="width:250px;font-size:10px;color:#333;">Daily Quotes by <a
            href="https://www.calendarlabs.com/" target="_blank" rel="nofollow"
            style="font-size:10px;text-decoration:none;color:#333;">CalendarLabs</a>
        </div>
      </div>
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