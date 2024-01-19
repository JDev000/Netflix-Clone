<div class="home-layout flex flex-col items-center h-2/3 justify-center md:justify-end mt-6">
    <div class="netflix-intro flex flex-col items-center justify-center text-center">
    <h1 class="mb-4 px-10 text-3xl md:text-5xl font-bold">
        Unlimited movies, TV shows, and more
      </h1>
      
      <p class="mb-4 px-4 text-xl md:text-2xl">
        Watch anywhere. Cancel anytime.
      </p>
      <p class="text-base px-4 md:text-xl mb-4">
        Ready to watch? Enter your email to create or restart your membership.
      </p>
    </div>
    <div class="netflix-button">
        <form action="/" class="flex items-center gap-4 md:gap-1 flex-col md:flex-row">
            <input
                type="email"
                name="email"
                placeholder="Email address"
                class="bg-transDark mr-1 pl-4 h-14 w-96 rounded border border-transLight"
            />
            <button class="btn relative h-12 md:h-14 text-xl pl-5 pr-16 rounded bg-pula">Get Started</button>
        </form>
    </div>
</div>

<style>
    .btn::after {
        content: url("../assets/next.png");
        position: absolute;
        top: 5%;
        right: 12%;
        height: 100%;
        width: 20%;
        display: flex;
        justify-content: center;
        align-items: center;
        transform: scale(0.9);
    }
</style>
