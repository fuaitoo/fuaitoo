<script>
  export let title, description
</script>

<section class="buildlog">
  <h3>{title}</h3>
  <p>{description}</p>
  <ul>
    <li>created 'fuaitoo' plenti site --bare based on plenti v.0.4.20<span class="date">/2021.05.31</span></li>
    <li>created 'buildlog' --single based from bodgie <span class="date">/2021.05.31</span></li>
    <li>added css from bodgie <span class="date">/2021.05.31</span></li>
    <li>moved everything from bodgie... <span class="date">/2021.05.31</span></li>
    <li>team member component <span class="date">/2021.06.01</span></li>
    <li>created "routes" inside plenti.json file <span class="date">/2021.06.02</span></li>
    <li>'featurecompo' and 'about' created<span class="date">/2021.06.02</span></li>
    <li>'attributions' created <span class="date">/2021.06.02</span></li>
    <li>updated fuaitoo to plenti v.0.4.21 <span class="date">/2021.06.02</span></li>
  </ul>
</section>

<style>
  .buildlog {
    width: 100%;
    height: 100vh;
    background-color: linen;
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
