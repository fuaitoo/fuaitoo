<script>
  import Head from './head.svelte';

  export let content, layout, title;
</script>

<html lang="en">
<Head title={ content.fields.title } />
<body>
  <svelte:component this={layout} {...content.fields} />
  <script src="https://kit.fontawesome.com/80f1b342a4.js" crossorigin="anonymous"></script>
  <footer>
    <div>copyright &copy; 2021, {title}</div>
  </footer>
</body>
</html>

<style>
  footer {
    font-family: 'Raleway', sans-serif;
    text-align:  center;
    font-size: 1.5rem;
    font-weight: 100;
    color:  white;
    background-color: hsl(205, 79%, 66%);
    padding: 8px;
  }
</style>
