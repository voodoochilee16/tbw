<svelte:head>
    <title>
        The Black Wizards
    </title>
</svelte:head>

<script>

</script>

<main>
   
    <div class="logo">
        <div class="collapse">
            <input type="checkbox" /> 
            <div class="collapse-title text-xl font-medium">
            The Black Wizards
            </div>
            <div class="collapse-content"> 
                <ul class = "links">
                    <a href="">Music</a>
                    <a href="">Tour</a>
                    <a href="">Merch</a>
                    <a href="">Media</a>
                    <a href="">Contact</a>
                </ul>
            </div>
        </div>
    </div>
  
</main>



<style>
    .logo{
        display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  min-height: 100vh;
}

    .links {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        gap: 1rem;
    }
</style>