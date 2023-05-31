<script>


    import { onMount } from "svelte";
    import Card from "./lib/Card.svelte";
    let nombre = "";
    
  
  onMount(() => {
  fetch('https://random-data-api.com/api/v2/users')
    .then(response => response.json())
    .then(({nombre, apellidos}) => nombre = `${nombre} ${apellidos}`)
})
  
</script>
  
  <main>
    <Card fullUserName="Minerva Pedret Vergillos" />
  </main>
  