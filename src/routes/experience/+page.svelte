<script>
    import Card from "../../lib/assets/components/Card.svelte";
    let fullyhacks = '/fullyhacks.jpeg';
    let acm = '/ACM.jpg';
    let cerebral = '/cerebral.jpg'
    let shpe = '/shpe-csuf.png';
</script>

<h1 class="text-7xl text-center m-11">Experience</h1>
<div class="grid grid-cols-3 col-span-full my-20 gap-8">
    <Card>
        <img src={acm} alt="ACM CSUF logo">
        <h3 class="text-2xl my-2">Association for Computing Machinery (ACM) - CSUF Student Chapter</h3>
        <p class="text-xl my-2">August 2023 - Present</p>
        <p class="my-3 text-xl">
            As a member of the largest tech organization in the CSUF campus, I have contributed to the club's open source software team,
            where I aided in maintaining the club's website and brainstorming ideas for future open source projects to benefit ACM's technical components.
            I am also an officer for the club's Development (Dev), where I collaborate with other officers in presenting hands-on workshops centering 
            around software development tools and tricks, as well as best practices for approaching project creation and resources to get started with 
            building projects to showcase their technical experience.
        </p>
    </Card>
    <Card>
        <img src={fullyhacks} alt="Fullyhacks 2024 Logo">
        <h2 class="text-2xl my-2">Fullyhacks 2024</h2>
        <p class="text-xl my-2">February 2024</p>
        <p class="my-3 text-xl">
            On February 25th-26th, 2024, I participated in Cal State Fullerton's annual hackathon, with over 300 competitors across various Southern
            California campuses, including Fullerton, UC Irvine, and UC Riverside.
        </p>
    </Card>
    <Card>
        <img class="size-48" src={cerebral} alt="Cerebral Beach Hacks logo">
        <h2 class="text-2xl my-2">Cerebral Beach Hacks</h2>
        <p class="text-xl my-2">October 2024</p>
        <p class="text-xl my-3">
            On October 12th-13th, 2024, I took park in the largest public hackathon in Los Angeles, hosted by AILA.
            This GenAI Hackathon was sponsored by notable names in the field of AI, including Twelve Labs, WhiteRabbitNeo, and
            Kindo.
        </p>
    </Card>
    <Card>
        <img class="" src={shpe} alt="Society of Hispanic Professional Engineers (SHPE) at CSUF Logo">
        <h2 class="text-2xl my-2">Society of Hispanic Professional Engineers (SHPE) - CSUF Student Chapter</h2>
        <p class="text-xl my-2">November 2024 - Present</p>
        <p class="my-3 text-xl">
            As the Webmaster and Marketing Director of SHPE @ CSUF, I am responsible for the development and maintenance of the chapter’s website, 
            along with creating flyers and posting on our social media accounts for our weekly workshops composed of resumé building activities, 
            guest speakers from various companies, and mock interviews. 
            I also lead our chapter’s open-source software committee, Dev-SHPE, which specializes in contributions to open-source projects that 
            ease workflows within our chapter and aim to attract other pupils within the CSUF campus.
        </p>
    </Card>
</div>



