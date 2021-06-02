<script>
  import Feature from '../components/featurecompo.svelte';
  import About from '../components/about.svelte';
  import Landing from '../components/landingdos.svelte';
  import WhoIsFuaitoo from '../components/whoisfuaitoo.svelte';
  import TallFooter from '../components/tallfooter.svelte';

	export let title;
</script>

<Landing {title}/>
<Feature />
<div id="about">
  <About {title}/>
</div>
<WhoIsFuaitoo />
<TallFooter {title}/>
<!-- <footer>
  <div>copyright &copy; 2021, {title}</div>
</footer> -->

<style>
  .proto {
    min-height: 100vh;
  }
</style>
