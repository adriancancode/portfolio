<script>
    import "../app.css";
    import '@fortawesome/fontawesome-free/css/all.min.css';
</script>
  
<nav class="bg-neutral-300 shadow-xl flex gap-10py-2 px-5 sticky">
    <a class="text-2xl p-4 transition ease-in-out rounded-lg hover:bg-neutral-100 active:opacity-70" href="/">
        Home
    </a>
    <a class="text-2xl p-4 transition ease-in-out rounded-lg hover:bg-neutral-100 active:opacity-70" href="/about">
        About Me
    </a>
    <a class="text-2xl p-4 transition ease-in-out rounded-lg hover:bg-neutral-100 active:opacity-70" href="/projects">
        Projects
    </a> 
    <a class="text-2xl p-4 transition ease-in-out rounded-lg hover:bg-neutral-100 active:opacity-70" href="/experience">
        Experience
    </a>
    <a class="text-2xl p-4 transition ease-in-out rounded-lg hover:bg-neutral-100 active:opacity-70" href="/contact">
        Contact Me
    </a>
</nav>

<slot />

