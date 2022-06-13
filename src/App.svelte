<script>
  import Select from './lib/Select.svelte'

  let options = [
    {id:'sl', value:'sri lanka'},
    {id:'pak', value:'pakistan'},
    {id:'ind', value:'india'}
  ]
</script>

<main>
  <Select {options} selectSize="larger"/>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

</style>
