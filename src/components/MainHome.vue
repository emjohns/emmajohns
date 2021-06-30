<template>
  <div class="home-main">
    <section class="main-top">
      <div class="top-top">
        <div class="container">
          <div class="row d-flex">
            <div class="col-lg-6 col align-self-end">
              <h1>Emma Johnson</h1>
              <h3>Senior Frontend Engineer</h3>
            </div>
            <div class="col-lg-6 col align-self-center">
              <div class="enter-quote">
                <span :class="{ appeared: quote.show }" v-for="quote in quoteList" :key="quote.index">{{ quote.sentence }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="bottom-top">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col">
              <img class="profile-pic" src="../assets/emjohnsprofilepic.jpeg" alt="Emma Johnson">
            </div>
          </div>
          <div class="row">
            <div class="col">
              <p>Hello World!</p>
              <p>My name’s Emma and I’m an artsy, math kid from Durham, NC. I got into coding after working various art production jobs after graduating college. After a few years of creating bow ties, floral arrangements, and custom fabrics, I found my calling making websites and web applications instead. I love my chosen career and am excited to continue to grow and challenge myself every day.</p>
              <p>If I had you at bow ties, go to <a href="https://www.brackishbowties.com/" target="_blank">brackishbowties.com</a>. If you’d like to see what I’ve been put to since then, keep scrolling and check out some of my recent projects. Enjoy!</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="main-primary-examples">
      <div class="example" id="example01">
        <div class="example-bg"></div>
        <div class="container">
          <div class="row d-lg-flex">
            <div class="col-md-6 col order-md-2 align-self-center col-12">
              <div class="example-img">
                <img class="img-fluid" alt="GoSokal.com" src="../assets/gosokal-06-22-21.gif">
              </div>
            </div>
            <div class="col-md-6 col order-md-1 align-self-center col-12">
              <div class="example-text">
                <h3>Go Sokal</h3>
                <p>After my first year of working at the company Webstreak, Webstreak and our sister company Sokal decided to merge. The very first question I had for the leadership was ‘Can we redesign the website?’ I met with various creatives throughout the company to discuss new logos, colors, and potential ideas for the new site. Then the frontend team and I designed a brand new site that we were able to launch within the month. I was responsible for over 90% of the code. A UX/UI designer and I continue to rework, improve, and update the site as our company evolves and develops new, exciting products.</p>
                <a href="https://www.gosokal.com/" target="_blank">View Site</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="example02" class="example">
        <div class="example-bg"></div>
        <div class="container">
          <div class="row d-lg-flex">
            <div class="col-md-6 col order-lg-1 col-12 align-self-center">
              <div class="example-img">
                <img class="img-fluid" alt="Momentum" src="../assets/momentum-06-22-21.gif">
              </div>
            </div>
            <div class="col-md-6 col order-lg-2 col-12 align-self-center">
              <div class="example-text">
                <h3>Momentum</h3>
                <p>Momentum is a robust application my company has created to process all our reporting across campaigns, tracking, and website activity. The backend is built with Ruby on Rails and the frontend is built with VueJS. I’ve had my hands in various aspects of this app, from debugging data and graph issues to redesigning the entire user experience and overall look and then applying those changes. This is just one example where I’ve worked as part of the development team from start to finish as we created a personalized product that has allowed our company to work easier and better serve our clients.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="example03" class="example">
        <div class="example-bg"></div>
        <div class="container">
          <div class="row d-lg-flex">
            <div class="col-md-6 col order-md-2 col-12 align-self-center">
              <div class="example-img">
                <img class="img-fluid" alt="Dealer Draft" src="../assets/dealerdraft-06-22-21.gif">
              </div>
            </div>
            <div class="col-md-6 col order-md-1 col-12 align-self-center">
              <div class="example-text">
                <h3>DealerDraft</h3>
                <p>My company has over 150 live car dealership sites and we only continue to make more. To do this efficiently, we have various website components within our website building application that can be repeated from site to site and easily customized by the web team. I noticed the account team who are often the ones to determine how the websites look had no idea the range of components available to them and communication between them and web team was flawed. I catalogued every component and built an app that allows a user to not only see what’s available, but search and filter results, rearrange chosen items, preview their site, and then download a png file. This has made a lot of people’s lives easier and hopefully has encouraged more variety between sites.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="main-secondary-examples">
      <div class="container">
        <div class="row">
          <div class="col">
            <h3>Other Projects</h3>
          </div>
        </div>
        <div class="row d-md-flex align-items-stretch">
          <div class="col-12 col-lg-4">
            <div class="other-box d-flex align-items-start flex-column">
              <div class="other-text align-self-start mb-auto">
                <h4>CAHEC</h4>
                <p>Brand new website coded from scratch for an affordable housing company in Raleigh.</p>
                <a href="https://www.cahec.com/" target="_blank">View Site</a>
              </div>
              <div class="overlay-box">
                <div class="other-img align-self-baseline">
                  <div class="img-foreground"></div>
                  <img class="img-fluid" alt="CAHEC Website" src="../assets/screencapture-cahec-21.png">
                </div>
                <div class="other-overlay"></div>
              </div>
            </div>
          </div>
          <div class="col-12 col-lg-4">
            <div class="other-box d-flex align-items-start flex-column">
              <div class="other-text align-self-start mb-auto">
                <h4>Stonecrest Honda</h4>
                <p>Created new designs for a client looking to overhaul their website and implemented changes.</p>
                <a href="https://www.stonecresthonda.com/" target="_blank">View Site</a>
              </div>
              <div class="overlay-box">
                <div class="other-img double-img align-self-baseline stonecrest-img">
                  <div class="img-foreground"></div>
                  <img class="img-fluid img-front" alt="Stonecrest Website" src="../assets/hondaconyers01copy.png">
                  <img class="img-fluid img-back" alt="Stonecrest Website" src="../assets/hondaconyers02copy.png">
                </div>
                <div class="other-overlay"></div>
              </div>
            </div>
          </div>
          <div class="col-12 col-lg-4">
            <div class="other-box d-flex align-items-start flex-column">
              <div class="other-text align-self-start mb-auto">
                <h4>Military Auto Source</h4>
                <p>Worked on design team to redesign and create new user experience for robust dealer website.</p>
              </div>
              <div class="overlay-box">
                <div class="other-img double-img align-self-baseline mas-img">
                  <img class="img-fluid img-front" alt="MAS Website" src="../assets/MASSRPNewMobilec.png">
                  <img class="img-fluid img-back" alt="MAS Website" src="../assets/MASVDPNewMobilec.png">
                </div>
                <div class="other-overlay"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'MainHome',
  data() {
    return {
      quoteList: [
        {sentence: 'I am a skilled developer who is', show: false},
        {sentence: 'passionate about creating', show: false},
        {sentence: 'beautiful, engaging, and', show: false},
        {sentence: 'responsive websites and web', show: false},
        {sentence: 'applications. I am an expert at', show: false},
        {sentence: 'translating ideas into reality', show: false},
        {sentence: 'through code.', show: false}
      ]
    }
  },
  mounted () {
    this.quoteList.forEach((quote, index) => {
      this.delayedShow(quote, index)
    })
  },
  methods: {
    delayedShow (item, index) {
      let delay = 600 * index
      setTimeout(() => {
        item.show = true
      }, delay)
    }
  }
}
</script>

<style>
  .home-main {
    font-size: 16px;
    margin-top: -62px;
    background: #fff;
  }
  .home-main .main-top {
    background-image: url('../assets/bluewatercolorcroppedhead.png');
    background-size: 100%;
    background-repeat: no-repeat;
  }
  .home-main .top-top .row {
    padding-bottom: 15%;
    height: 100vh;
  }
  .home-main .top-top h1 {
    color: #fff;
    font-size: 4rem;
    font-weight: 700;
    text-shadow: 0px 3px 6px rgba(4, 50, 105, .3);
  }
  .home-main .top-top h3 {
    color: #fff;
    font-size: 2rem;
    font-weight: 300;
    text-transform: uppercase;
    text-shadow: 0px 3px 6px rgba(4, 50, 105, .3);
  }
  .home-main .top-top .enter-quote {
    padding-top: 30%;
  }
  .home-main .top-top .enter-quote span {
    color: #fff;
    font-size: 26px;
    font-weight: 500;
    text-shadow: 0px 3px 6px rgba(4, 50, 105, .3);
    opacity: 0;
    text-align: right;
    display: block;
    margin-bottom: 10px;
    transform: translate(-20px,10px);
    -webkit-transition: all 0.8s ease;
    -moz-transition: all 0.8s ease;
    -o-transition: all 0.8s ease;
    transition: all .8s ease;
  }
  .home-main .top-top .enter-quote span.appeared {
    opacity: 1;
    transform: translate(0px,0px);
  }
  .home-main .bottom-top {
    padding-bottom: 30px;
    padding-top: 50px;
    text-align: center;
  }
  .home-main .bottom-top .profile-pic {
    border-radius: 100%;
    width: 100%;
    max-width: 320px;
    margin: auto auto 50px;
    display: block;
  }
  .home-main .bottom-top p {
    font-size: 18px;
    margin-bottom: 15px;
  }
  .home-main a {
    color: #2a79be !important;
    text-decoration: none;
    -webkit-transition: all 0.9s ease;
    -moz-transition: all 0.9s ease;
    -o-transition: all 0.9s ease;
    transition: all .9s ease;
  }
  .home-main .main-secondary-examples a:hover, .home-main .main-primary-examples a:hover {
    transform: translateY(-5px);
  }
  .home-main .example {
    position: relative;
    font-size: 16px;
  }
  .home-main .example .container {
    z-index: 10;
    padding-top: 5%;
    padding-bottom: 5%;
    position: relative;
  }
  .home-main .example .example-bg {
    position: absolute;
    top: 0;
    bottom: 0;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
    width: 800px;
    z-index: 0;
  }
  .home-main #example01 .example-bg, .home-main #example03 .example-bg {
    right: calc(50% - 650px);
  }
  .home-main #example02 .example-bg {
    left: calc(50% - 750px);
  }
  .home-main #example01 .example-bg {
    background-image: url('../assets/bluewatercolor101.jpg');
  }
  .home-main #example02 .example-bg {
    background-image: url('../assets/bluewatercolor102.jpg');
  }
  .home-main #example03 .example-bg {
    background-image: url('../assets/bluewatercolor103.jpg');
  }
  .home-main .example h3, .home-main .main-secondary-examples h3 {
    color: #2a79be;
    font-size: 36;
  }
  .home-main .main-secondary-examples {
    padding: 5% 0;
    font-size: 16px;
    text-align: center;
  }
  .home-main .other-box {
    margin: 0px auto 30px;
    height: 100%;
    text-align: center;
  }
  .home-main .main-secondary-examples h3 {
    margin-bottom: 30px;
  }
  .home-main .main-secondary-examples h4 {
    text-transform: uppercase;
    font-size: 20px;
    font-weight: 400;
    margin-bottom: 25px;
  }
  .home-main .main-secondary-examples a, .home-main .main-primary-examples a {
    margin-top: 15px;
    text-transform: uppercase;
    font-size: 18px;
    display: block;
  }
  .home-main .other-box .other-img {
    width: 100%;
    max-height: 400px;
    overflow: scroll;
    position: relative;
  }
  .home-main .other-box .overlay-box {
    position: relative;
    height: 400px;
    width: 100%;
  }
  .home-main .other-box .other-overlay {
    background: -moz-linear-gradient(top, rgba(0,0,0,0) 0%, rgba(0,0,0,0.52) 100%);
    background: -webkit-linear-gradient(top, rgba(0,0,0,0) 0%,rgba(0,0,0,0.52) 100%);
    background: linear-gradient(to bottom, rgba(0,0,0,0) 0%,rgba(0,0,0,0.52) 100%);
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: 20;
    height: 25px;
  }
  .home-main .other-box .double-img .img-back {
    z-index: 1;
    top: 0;
    left: 0;
    width: 250px;
    float: left;
  }
  .home-main .other-box .double-img .img-front {
    z-index: 10;
    top: 100px;
    right: 0;
    width: 250px;
    position: absolute;
  }
  .home-main .other-box .stonecrest-img .img-front {
    height: 760px;
  }
  .home-main .other-box .mas-img .img-front {
    height: 550px;
    width: 220px;
  }

  @media (min-width: 1400px) {
    .container {
      max-width: 1170px !important;
    }
  }

  @media (max-width: 1199px) {
    .home-main .top-top .enter-quote {
      padding-top: 15%;
    }
    .home-main .top-top .row {
      padding-bottom: 10%;
      height: 80vh;
    }
    .home-main .top-top .enter-quote span {
      font-size: 24px;
    }
    .home-main .bottom-top {
      padding-top: 0;
    }
    .home-main #example03 .example-bg {
      top: -35px;
    }
  }

  @media (max-width: 991px) {
    .home-main .top-top .enter-quote {
      padding-top: 0;
    }
    .home-main .top-top .row {
      padding-bottom: 10%;
      height: 600px;
    }
    .home-main .top-top .enter-quote span {
      font-size: 20px;
      margin-bottom: 5px;
    }
    .home-main .top-top h1 {
      font-size: 3.5rem;
    }
    .home-main .top-top h3 {
      font-size: 1.5rem;
    }
    .home-main .bottom-top .profile-pic {
      max-width: 275px;
    }
    .home-main .example .example-bg {
      width: 650px;
    }
    .home-main #example01 .example-bg, .home-main #example03 .example-bg {
      right: calc(50% - 575px);
    }
    .home-main #example02 .example-bg {
      left: calc(50% - 575px);
    }
    .home-main .other-box .other-text {
      width: 100%;
    }
    .home-main .other-box .overlay-box {
      max-width: 450px;
      margin: auto auto 50px;
    }
  }

  @media (max-width: 835px) {
    .home-main .top-top .row {
      height: 540px;
    }
  }

  @media (max-width: 767px) {
    .home-main .top-top .enter-quote span {
      font-size: 16px;
    }
    .home-main .top-top h1 {
      font-size: 3rem;
      line-height: 1;
    }
    .home-main .top-top .row {
      height: 425px;
    }
    .home-main .top-top .enter-quote {
      padding-top: 15%;
    }
    .home-main .top-top h3 {
      font-size: 1.3rem;
      line-height: 1;
      margin-bottom: 1rem;
    }
    .home-main .example .example-img {
      margin-bottom: 25px;
    }
    .home-main #example01 .example-bg, .home-main #example02 .example-bg, .home-main #example03 .example-bg {
      right: 0;
      top: -15px;
      left: calc(50% - 300px);
      width: 100%;
      max-width: 600px;
      background-position: top center;
    }
    .home-main .other-box .overlay-box, .home-main .other-box .other-img {
      height: 300px;
      max-height: 300px;
    }
  }

  @media (max-width: 575px) {
    .home-main .top-top .enter-quote span {
      font-size: 15px;
    }
    .home-main .top-top .row {
      height: unset;
      min-height: 400px;
    }
    .home-main .top-top .enter-quote {
      padding-top: 0;
    }
    .home-main .top-top h3 {
      margin-bottom: 2rem;
    }
    .home-main .main-top {
      background-size: 200%;
      background-position: 100% -10%;
    }
    .home-main .main-top .col-lg-6 {
      flex: none;
      text-align: center;
    }
    .home-main .main-top .align-self-end {
      padding-top: 100px;
    }
    .home-main .top-top .enter-quote span {
      text-align: center;
    }
    .home-main .bottom-top .profile-pic {
      margin-top: 50px;
    }
    .home-main #example01 .example-bg, .home-main #example02 .example-bg {
      right: -40px;
      left: -40px;
      top: -15px;
      width: calc(100% + 80px);
      max-width: unset;
    }
    .home-main #example03 .example-bg {
      right: -80px;
      left: -80px;
      width: calc(100% + 160px);
      max-width: unset;
      top: -10px;
    }
    .home-main .example .example-img img {
      width: 100%;
    }
  }
  @media (max-width: 420px) {
    .home-main .main-top {
      background-size: 348%;
      background-position: 68% -150%;
    }
    .home-main .main-top .align-self-end {
      padding-top: 70px;
    }
  }

  @media (max-width: 375px) {
    .home-main .main-top {
      background-size: 348%;
      background-position: 68% -43%;
    }
  }
</style>