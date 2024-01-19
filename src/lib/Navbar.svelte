<script>
    let langs = ["English", "Spanish", "French", "German"]
</script>

<nav class="custom-bg max-w-screen-lg mx-auto flex justify-between items-center  px-4 py-5 text-[clamp(1rem, 5vw, 2rem)">
    <ul class="flex">
        <li class="">
            <a href="https://fontmeme.com/netflix-font/">
                <img class="w-24 ml-0 md:w-26 md:ml-4 lg:w-36" src="https://fontmeme.com/permalink/240106/1b624094bfba82dd27d4bb77ea5acfcc.png" alt="netflix-font"/>
            </a>    
        </li>
    </ul>
    <ul class="flex items-center"> <!-- Added "items-center" class for centering items -->
        <li class="flex content-center mr-2 md:mr-5 py-1 px-4 bg-dilim border-slate-50 border-[rgba(255,255,255,.4)] border rounded">
            <label class="sm:hidden" for="lang">Lang</label>
            <select class="bg-dilim border-0 outline-none" id="lang" name="lang">
                {#each langs as lang}
                    <option value="{lang}" class="hidden">{lang}</option>
                {/each}
            </select>
        </li>
        <li class="flex content-center mr-4 py-1.5 px-4 bg-pula border-slate-50 border-pula border rounded"><a class="text-sm" href="/">Sign In</a></li>
    </ul>
</nav>

