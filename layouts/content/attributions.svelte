<script>
  export let title, description
</script>

<section class="attributions">
  <h3>{title}</h3>
  <p>{description}</p>
  <ul>
    <li>plenti</li>
    <li>svelte</li>
    <li>skeleton css</li>
    <li>eric meyer</li>
    <li>css tricks</li>
    <li>google fonts/raleway</li>
    <li>font awesome</li>
    <li>unsplash</li>
  </ul>
</section>

<style>
  .attributions {
    width: 100%;
    height: 100vh;
    background-color: mistyrose;
  }

    ul {
    grid-area: list;
    padding-bottom: 100px;
  }

  li {
    color: rgba(0,0,0,0.7);
    font-size: 1.6rem;
    list-style: none;
  }

  .date {
    color: lightskyblue;
    padding-left:  10px;
  }
</style>
