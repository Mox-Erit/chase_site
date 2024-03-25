<div class="container">
    <div class="hero">
        <div class="hero-title">
            <h1>Chase Alber</h1>
            <h2>Software Engineer</h2>
        </div>
        <div class="hero-img">
            <img id="photo" src="chase.jpg" alt="">
        </div>
    </div>
    <div class="links">
        <a href="https://github.com/Mox-Erit" target="_blank" aria-label="This link to github will open in a new window">github</a>
        <a href="https://twitter.com/_TowerTower" target="_blank" aria-label="This link to github will open in a new window">twitter</a>
        <a href="https://linkedin.com/in/chasealber/" target="_blank" aria-label="This link to github will open in a new window">linkedin</a>
        <a href="">models</a>
        <a href=""></a>
    </div>
    <div class="bio">
        Merhaba! My name is Chase and I am a Software Engineer with the State of Montana. I also tinker with embedded systems which I build out custom RC models and designs. In my free time you can find me slinging flies on the Missouri river or volunteering with my church.
    </div>
</div>


<style>
    .container {
        margin: 3rem auto;
        padding: 0.5rem;
        max-width: 650px;
    }
    .hero {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-wrap: wrap;
    }
    .hero-title {
        max-width: 350px;
    }
    .hero-img {
        position: relative;
        width: 250px;
        height: 250px;
        margin: 0 0 10px 0;
        border-radius: 50%;
        overflow: hidden;
    }
    .hero-img img {
        position: absolute;
        top: 50%;
        left: 50%;
        -webkit-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
        height: 100%;
    }
    .links {
        margin: 2rem 0;
    }
    .links a:not(:last-child) {
        padding: 0 12px 0 0;
    }
    .bio {
        line-height: 1.6;
        font-size: clamp(1rem, 0.96rem + 0.22vw, 1.125rem);
    }

    @media (max-width: 600px) {
        .container {
            padding: 1.3rem;
        }
        .links {
            text-align: center;
        }
    }

</style>