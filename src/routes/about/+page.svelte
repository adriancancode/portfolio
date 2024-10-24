<script>
    import Section from "../../lib/assets/components/Section.svelte";
    let snowboarding = "/snowboarding.jpg";
    let guitar = '/guitar.jpg';
    let gym = '/gym.jpg';
    let Longboard = '/Longboard.jpeg';
    let python = "/python.svg";
    let java = "/Java-Dark.svg";
    let c_plus_plus = 'CPP.svg';
    let c_lang = '/C.svg';
    let js = '/JavaScript.svg';
    let next = '/NextJS-Dark.svg';
    let svelte = '/Svelte.svg';
    let tailwind = '/TailwindCSS-Dark.svg';
</script>

<h1 class="text-7xl text-center m-11">About Me</h1>
<h2 class="text-5xl mx-52 underline">Biography</h2>
<Section>
    <p class="text-2xl">
        I am currently a third year Computer Science student at California State University, Fullerton.
        I started my coding journey in Fall 2022 going into my freshman year, and ever since have adored the countless 
        possibilities of software that have come into my life.  I am beyond eager to share my growth in the tech field with you.
    </p>
</Section>
    

<br/>

<h2 class="text-5xl mx-52 underline">Skills</h2>
<Section>
    <h3 class="text-4xl">Languages</h3>
    <div class="m-20 flex flex-row justify-center align-middle flex-wrap gap-8">
        <img src={python} alt="Python language logo" class="w-36">
        <img src={java} alt="Java language logo" class="w-36">
        <i class="fa-brands fa-html5 fa-10x text-orange-600"></i>
        <i class="fa-brands fa-css3-alt fa-10x text-blue-600"></i>
        <img class="size-40" src={js} alt="Javascript logo">
        <img class="size-40" src={c_plus_plus} alt="C++ logo">
        <img class="size-40" src={c_lang} alt="C language logo">

    </div>
    <h3 class="text-4xl">Component and meta frameworks</h3>
    <div class="m-20 flex flex-row justify-center align-middle flex-wrap gap-8">
        <i class="fa-brands fa-react fa-10x text-cyan-400"></i>
        <img src={svelte} alt="Svelte banner" class="w-36">
        <img src={next} alt="NextJS banner" class="w-36">
        <img src={tailwind} alt="TailwindCSS banner" class="w-36">
    </div>
   

</Section>
    

<h2 class="text-5xl mx-52 underline">Hobbies</h2>
<div class="flex flex-row flex-wrap justify-center w-full my-20 gap-8">
    <div class="w-1/4 shadow-lg p-6 rounded-md">
        <img src={guitar} alt="Adrian playing an electric guitar in a music room.">
        <p class="text-3xl text-center mt-5">Playing the guitar</p>
    </div>
    
    <div class="w-1/4 shadow-lg p-6 rounded-md">
        <img src={snowboarding} alt="Adrian on a ski lift in Mountain High Resort, Wrightwood, CA.">
        <p class="text-3xl text-center mt-5">Snowboarding</p>
    </div>
    <div class="w-1/4 shadow-lg p-6 rounded-md">
        <img src={gym} alt="Adrian sitting on a bench taking a mirror selfie at the gym">
        <p class="text-3xl text-center mt-5">Going to the gym</p>

    </div>
    <div class="w-1/4 shadow-lg p-6 rounded-md">
        <img src={Longboard} alt="Adrian riding a longboard through the CSUF campus">
        <p class="text-3xl text-center mt-5">Longboarding</p>
    </div>
</div>

    







