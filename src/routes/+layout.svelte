<script>
    import Navbar from '$lib/Navbar.svelte'
    import Home from '$lib/Home.svelte';
    import "../main.css"
</script>

<div class = "netflix-bg">
    <div class="light-collage">
        <Navbar/>
        <Home/>
    </div>
</div>
<slot/>


<style>
    .netflix-bg{
        background: url(../assets/netflix-bg.jpg) no-repeat;
        background-size: cover;
        background-position: center;
        height: 100vh;
    }

    
    .light-collage{
            background: rgba(0,0,0, .7);
            height: 100vh;
        }
    


</style>
