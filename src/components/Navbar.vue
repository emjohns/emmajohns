<template>
  <div class="default-nav">
    <b-navbar toggleable="md">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <div class="container">
          <div class="row">
            <div class="col">
              <b-navbar-nav class="mr-md-3 justify-content-end">
                <b-nav-item href="https://www.linkedin.com/in/emmajohnson00/" target="_blank">Linked In</b-nav-item>
                <b-nav-item href="https://github.com/emjohns" target="_blank">Github</b-nav-item>
                <b-nav-item class="nav-spacer"></b-nav-item>
              </b-navbar-nav>
            </div>
          </div>
        </div>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {

  }
}
</script>

<style>
  .default-nav {
    background: transparent;
  }
  .default-nav .navbar {
    background: transparent;
    position: relative;
  }
  .default-nav .navbar a {
    color: #2a79be !important;
    font-weight: 500;
    text-decoration: none !important;
    text-transform: uppercase;
    font-size: 20px;
    outline: none !important;
    background: transparent !important;
    position: relative;
  }
  .default-nav .navbar a:after {
    display: block;
    content: " ";
    position: absolute;
    left: 50%;
    bottom: 0;
    width: 0;
    transition: all 0.3s ease-in-out;
    height: 2px;
    background-color: #2a79be;
  }
  .default-nav .navbar a:hover::after, .default-nav .navbar a:focus::after {
    width: 100%;
    left: 0%;
}

  @media (min-width: 768px) {
    .default-nav .navbar a {
      padding-right: 1rem;
      padding-left: 1rem;
    }
    .default-nav .nav-spacer {
      width: 100px;
    }
  }

  @media (max-width: 767px) {
    .default-nav .navbar-toggler {
      border: none;
      outline: none !important;
      box-shadow: none !important;
    }
    .navbar-collapse.collapse {
      position: absolute;
      top: 100%;
      left: 15px;
      background: #fff;
      padding: 0px 15px 0;
      box-shadow: 0px 3px 6px rgba(4, 50, 105, .3);
      -webkit-transition: all 0.3s ease;
      -moz-transition: all 0.3s ease;
      -o-transition: all 0.3s ease;
      transition: all .3s ease;
    }
    .navbar-collapse.collapse.show {
      padding: 15px 15px 0;
    }
  }
</style>