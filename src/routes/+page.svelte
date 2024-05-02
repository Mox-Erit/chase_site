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

    <div class="bio">
        <p>Ahoy! Right now I am working on my RC model of the Lockheed "Sea Shadow" - which I am programming using the Elixir Nerves framework.
            <br/><br/>I am modeling, 3D printing, and assembling it all together in my free time. And I hope to share a full tutorial on this soon!</p> 
    </div>
    <div class="links">
        <a href="https://github.com/Mox-Erit" target="_blank" aria-label="This link to github will open in a new window">github</a>
        <a href="https://linkedin.com/in/chasealber/" target="_blank" aria-label="This link to github will open in a new window">linkedin</a>
        <a href="/models">models</a>
        <a href="/books">books</a>
    </div>
</div>


<style>
    .container {
        margin: 10px auto;
        padding: 5px;
        max-width: 650px;
    }
    .hero {
        display: flex;
        align-items: center;
        justify-content: space-around;
        flex-wrap: wrap;
    }
    .hero-title {
        max-width: 350px;
    }
    .hero-img {
        position: relative;
        width: 300px;
        height: 300px;
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
        justify-content: space-between;
        display: flex;
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