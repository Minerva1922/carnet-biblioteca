<script>
    export let fullUserName;
    let lista = fullUserName.split(" ")
    let name = "";


</script>

<div class="card">
    <h3>{fullUserName}</h3>
   <p>nom: Minerva </p>
   <p>cognoms: Pedret Vergillos</p>
</div>

<style>
    .card {
        background-color: #f5f5f5;
        padding: 16px;
        border-radius: 4px;
        box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
    }
</style>
