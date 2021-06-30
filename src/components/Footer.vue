<template>
  <div class="default-foot">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col">
          <a class="float-right" href="https://www.linkedin.com/in/emmajohnson00/" target="_blank">
            <img src="../assets/linkedin-white.svg" alt="Linked In Icon"/>
          </a>
        </div>
        <div class="col">
          <a href="https://github.com/emjohns" target="_blank">
            <img src="../assets/github-white.svg" alt="Github Icon"/>
          </a>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <p class="copyright">Copyright © Emma Johnson 2021</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    
  }
}
</script>

<style>
  .default-foot {
    color: #fff;
    background-image: url('../assets/bluewatercolorcroppedfooter.png');
    background-size: cover;
    background-position: top;
    padding-top: 20%;
  }
  .default-foot img {
    height: 50px;
    -webkit-transition: all 0.3s ease;
    -moz-transition: all 0.3s ease;
    -o-transition: all 0.3s ease;
    transition: all .3s ease;
  }
  .default-foot a.float-right {
    float: right;
  }
  .default-foot a:hover, .default-foot a:focus, .default-foot a:active {
    text-decoration: none;
    outline: none !important;
  }
  .default-foot img:hover, .default-foot img:active, .default-foot img:focus {
    opacity: .7;
    outline: none !important;
  }
  .default-foot p {
    color: #fff;
    font-size: 13px;
    margin: 15% 0 20px;
    text-shadow: 0px 3px 6px rgba(4, 50, 105, .4);
  }
</style>