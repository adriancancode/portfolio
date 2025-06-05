<script>
    import Card from "../../lib/assets/components/Card.svelte";
    let fullyhacks = '/fullyhacks.jpeg';
    let acm = '/ACM.jpg';
    let cerebral = '/cerebral.jpg'
</script>

<h1 class="text-7xl text-center m-11">Experience</h1>
<div class="flex flex-row flex-wrap justify-center w-full gap-8">
    <Card>
        <img src={acm} alt="ACM CSUF logo">
        <h3 class="text-2xl my-2">Association for Computing Machinery - CSUF Student Chapter</h3>
        <p class="text-xl my-2">August 2023 - Present</p>
        <p class="my-3 text-xl">
            As a member of the largest tech organization in the CSUF campus, I am currently contributing to the club's open source software team,
            where I aid in maintaining the club's website and brainstorm ideas for future open source projects to benefit ACM's technical components.
            I am also an officer for the club's marketing team, where I assist in spreading the word of the club's weekly workshops, events,
            and career opportunities by means of social media(Instagram, TikTok), flyer-making, and photography.
        </p>
    </Card>
    <Card>
        <img src={fullyhacks} alt="Fullyhacks 2024 Logo">
        <h2 class="text-2xl my-2">Fullyhacks 2024</h2>
        <p class="my-3 text-xl">
            On February 25th-26th, 2024, I participated in Cal State Fullerton's annual hackathon, with over 300 competitors across various Southern
            California campuses, including Fullerton, UC Irvine, and UC Riverside.
        </p>
    </Card>
    <Card>
        <img class="size-48" src={cerebral} alt="Cerebral Beach Hacks logo">
        <h2 class="text-2xl my-2">Cerebral Beach Hacks</h2>

        <p class="text-xl my-3">
            On October 12th-13th, 2024, I took park in the largest public hackathon in Los Angeles, hosted by AILA.
            This GenAI Hackathon was sponsored by notable names in the field of AI, including Twelve Labs, WhiteRabbitNeo, and
            Kindo.
        </p>
    </Card>
</div>



