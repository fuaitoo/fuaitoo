<script>
  let tallfooterBgImage = 'assets/images/toa-heftiba.jpg';

  export let title;
</script>

<div>
  <div class="bgfx" style="background-image: url({tallfooterBgImage});">
  </div>
  <!-- colored slide -->

  <div class="bgfx halfy" style="background-image: url({tallfooterBgImage});">
    <div class="section-break-shade"></div>
  </div>
  <!-- shaded slide -->
</div><!-- section break fx -->

<footer class="isFlex">
  <div class="isLogo">
    <h3>{ title }</h3>
    <p>play with all.</p>
    <p>fair to all.</p>
    <p>buy now.</p>
  </div>
  <div class="isExplore">
    <h3 class="isHeading">explore</h3>
    <a href="/">home</a>
    <a href="#about">about</a>
    <a href="blog">author's commentaries</a>
    <a href="/buildlog">dev.log</a>
    <a href="attributions">attributions</a>
  </div>
  <div class="isAddresses">
    <h3 class="isHeading">visit</h3>
    <p>
      no. 45 hon. benito soliven st.,<br>
      cainta-greenpark,<br>
      cainta, rizal —1900
    </p>
    <p>new business</p>
    <p>fuaitoo@gmail.com</p>
    <p>+63.921.980.5015</p>
  </div>
  <div class="isSocialMedia flex flex-col">
    <h3 class="isHeading">follow</h3>
    <div class="isIcon">
      <a href=""><i class="awesome fab fa-facebook-messenger fa-2x"></i></a>
      <a href=""><i class="awesome fab fa-facebook fa-2x"></i></a>
      <a href=""><i class="awesome fab fa-twitter fa-2x"></i></a>
      <a href=""><i class="awesome fab fa-instagram fa-2x"></i></a>
      <a href=""><i class="awesome fab fa-github fa-2x"></i></a>
      <a href=""><i class="awesome fab fa-pinterest fa-2x"></i></a>
    </div>
  </div>
  <div class="isLegal">
    <h3 class="isHeading">legal</h3>
    <a href="/">terms</a>
    <a href="/">privacy</a>
  </div>
</footer>

<style type="text/css">
  .bgfx {
    background: no-repeat bottom center fixed;
    background-size: cover;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    height: 100vh;
    overflow: hidden; /* clears white space above div! yey! */
  }

  .halfy {
    height: 50vh;
  }

  .section-break-shade {
    background-color: hsla(0, 0%, 5%, 0.9);
    width: 100%;
    height: 100vh;
  }

  .bg-pos {
    /*background-position: 0% 15%;*/
  }

  footer {
    color: hsla(0, 0%, 88%, .85);
    font-weight:  200;
    /*letter-spacing: 1px;*/
    /*font-family: 'Raleway', sans-serif;*/
    height: 60vh;
    background-color: hsla(250, 100%, 0%, 90%);
    padding: 20px 10px;
  }

  .isFlex {
    justify-content: space-between;
    padding: 0 250px;
    padding-top: 100px;
  }

  h3 {
    font-size: 1.6rem;
    font-weight: 300;
  }

  .isExplore,
  .isAddresses,
  .isSocialMedia,
  .isLegal {
    color:  inherit;
  }

  .isExplore a,
  .isLegal a,
  .isIcon a {
    display: block;
    text-decoration: none;
    color:  inherit;
  }

  .isExplore a:hover,
  .isSocialMedia a:hover,
  .isLegal a:hover {
    color:  hsla(43, 96%, 58%, .75);
    color:  lightskyblue;
  }

  .isExplore a,
  .isLegal a {
    padding-bottom: 10px;
  }

  .isIcon a {
    padding-bottom: 20px;
  }
</style>
