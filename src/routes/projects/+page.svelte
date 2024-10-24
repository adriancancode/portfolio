<script>
    let chef_ai = "/chef-ai2.jpg";
    let spring = '/spring_facts.jpg';
    let frightframes = '/frightframes.jpg';
</script>
<h1 class="text-7xl text-center m-11">Projects</h1>
<div class="flex flex-row flex-wrap justify-center w-full gap-8">
    <div class="flex flex-col items-center justify-center w-1/4 p-6 shadow-lg rounded-md">
        <img src={chef_ai} alt="Recipe card of Chef-AI app with example recipe of breakfast burrito with full ingredients list and steps on how to make it">
        <h3 class='text-3xl my-2'>Chef-AI</h3>
        <p class='my-3 text-xl'>
            Recipe finder app submitted for my software engineering foundations class.  Utilizes the OpenAI API to 
            fetch AI-generated recipes via user ingredient input.
        </p>
        
        <button class="bg-neutral-300 transition ease-in-out hover:bg-neutral-100 active:opacity-70 p-3 rounded-lg font-bold text-xl mt-20"><a href="https://github.com/guidoasbun/recipe-finder-se" target="_blank">Github Repository</a></button>
    </div>
    <div class="flex flex-col items-center justify-center w-1/4 p-6 shadow-lg rounded-md">
        <img src={spring} alt="Screenshot of spring fun facts website home page">
        <h3 class="text-3xl my-7">Spring Fun Facts</h3>
        <p class='my-3 text-xl'>A silly and interactive website project made as a submission for ACM CSUF BunnyHacks 2024.</p>
        
        <button class="bg-neutral-300 transition ease-in-out hover:bg-neutral-100 active:opacity-70 p-3 rounded-lg font-bold text-xl mt-20"><a href="https://github.com/adriancancode/Bunnyhacks-24" target="_blank">Github Repository</a></button>

    </div>
    <div class="flex flex-col items-center justify-center w-1/4 p-6 shadow-lg rounded-md">
        <img src={frightframes} alt="Front Page of FrightFrames project, submission for Cerebral Beach Hacks 2024">
        <h3 class="text-3xl my-7">FrightFrames</h3>
        <p class='my-3 text-xl'>Horror movie trailer storyboard made as a submission for Cerebral Beach Hacks 2024.</p>
        <button class="bg-neutral-300 transition ease-in-out hover:bg-neutral-100 active:opacity-70 p-3 rounded-lg font-bold text-xl mt-20"><a href="https://github.com/adriancancode/Cerebral_Beach_Hacks_2024" target="_blank">Github Repository</a></button>
    </div>
</div>


