<script>
  // export let bgImage = '../assets/hotStuff/jessierogers-01.jpg';
</script>

<section class="whoisfuaitoo">
  <div class="container isFlex">
  <div class="card">
    <img
      src="./assets/teammembers/designerguy.png"
      alt="designer guy"
      style="background-color: hsla(67, 50%, 71%, 0.87);"
    >
    <h3 class="name">claxx moldii</h3>
    <h4 class="title">designir</h4>
    <p>

    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/recordsguy.png"
      alt="records guy"
      style="background-color: hsla(215, 50%, 71%, 0.87);"
    >
    <h3 class="name">tane "banane" street-A</h3>
    <h4 class="title">rekidds keepur</h4>
    <p>
      keeps record albums tidy and shiny. makes sure that records are scratch-free.
    </p>
    <p>
      also in charge of filing stuff away.
    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/cartoonguy.png"
      alt="cartoon guy"
      style="background-color: hsla(335, 100%, 86%, 0.77)"
    >
    <h3 class="name">guilberto manawis</h3>
    <h4 class="title">illy-straightir/letturer</h4>
    <p>
      makes sure that the illy coffee cans are always in a straight line. not to be confused for fixing coffee. just keeping cans tidy.
    </p>
    <p>
      he also draws and letters.
    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/fixitguy.png"
      alt="cartoon guy"
      style="background-color: hsla(67, 50%, 71%, 0.87);"
    >
    <h3 class="name">claxx moldii</h3>
    <h4 class="title">fix-it persin</h4>
    <p>
      in charge of repairs. also in charge of paying for things broken during his repairs.
    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/callcenterguy.png"
      alt="records guy"
      style="background-color: hsla(215, 50%, 71%, 0.87);"
    >
    <h3 class="name">tane "banane" street-A</h3>
    <h4 class="title">informayshin persin</h4>
    <p>
      answers all calls.
    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/deliveryguy.png"
      alt="delivery guy"
      style="background-color: hsla(335, 100%, 86%, 0.77);"
    >
    <h3 class="name">guilberto manawis</h3>
    <h4 class="title">delivery persin</h4>
    <p>
      in charge of putting stuff in boxes and shipping out. but not labeling. that's the letturer's job. stuff sent out ranges from rusty bent soda pop cap to... what ever's sitting next to the rusty bottle cap.
    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/cookguy.png"
      alt="cook guy"
      style="background-color: hsla(67, 50%, 71%, 0.87);"
    >
    <h3 class="name">claxx moldii</h3>
    <h4 class="title">cooking guy</h4>
    <p>
      either it's for two or two hundred, cooking guy will cook spaghetti for you. if there are two hundred of you, he'll cook the whole bag. there's enough in the bag for two hundred.
    </p>
    <p>
      fixes the tomato sauce when cooking for himself.
    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/coffeeguy.png"
      alt="coffee guy"
      style="background-color: hsla(215, 50%, 71%, 0.87);"
    >
    <h3 class="name">tane "banane" street-A</h3>
    <h4 class="title">coffee-making guy</h4>
    <p>

    </p>
  </div>
  <div class="card">
    <img
      src="./assets/teammembers/musicguy.png"
      alt="music guy"
      style="background-color: hsla(335, 100%, 86%, 0.77);"
    >
    <h3 class="name">guilberto manawis</h3>
    <h4 class="title">moo-sick guy</h4>
    <p>
      kkoona t'chuta Solo? soong peetch alay. nuklee numaa. ches ko ba tuta creesta crenko ya kolska.
    </p>
  </div>
</div>
</section>

<style>
  .whoisfuaitoo {
    max-width: 100%;
    min-height: 100vh;
    background-color: hsla(350, 100%, 90%, .7);
    padding: 50px;
    /*padding-top: 100px;*/
  }

  .isFlex {
    flex-flow: row wrap;
    justify-content: space-between;
  }

  .container {
    max-width:  70%;
    /*background-color: beige;*/
  }

  .card {
    width: 250px;
    background-color: hsla(307, 12%, 100%, 0.56);
    margin-bottom: 50px;
    margin-right: 25px;
    padding: 50px 25px;
    display: flex;
    flex-direction: column;
    align-items: center;
    border-radius: 15px;
  }

  img {
    height: 150px;
    width:  auto;
    border: #f5f5f5 solid 5px;
    border-radius: 50%;
    /*align-self:  center;*/
  }

  .name,
  .title {
    margin: 0;
  }

  .name {
    font-size:  2rem;
    font-weight: 400;
  }

  .title {
    font-size:  1.7rem;
    font-weight: 300;
    color:  grey;
  }

  p {
    margin: 0;
    padding-top: 10px;
    max-width: 180px;
  }
</style>
