<div class="container">
    <div class="current section">
        <div class="book">
            <img class="book-img" src="weather-e.jpg" alt="" />
            <p class="book-desc">Going through this book as part of my RC project development and to hopefully incorporate in automating my garden.</p>
        </div>
    </div>
    <div class="next section">
        <div class="book">
            <img src="" alt="" />
            <p></p>
        </div>
    </div>
    <div class="past section">
        <div class="book">
            <img src="" alt="" />
            <p></p>
        </div>
    </div>
</div>


<style>
    .container {
        margin: 50px auto;
        padding: 5px;
        max-width: 650px;
    }
    .current {
        border: blue solid 2px;
        border-radius: 25px;
        padding: 30px;
        display: flex;
    }
    .next {
        border: green solid 2px;
    }
    .past {
        border: purple solid 2px;
    }
    .book {
        display: flex;
    }
    .book-img {
        display: block;
        height: 300px;
        width: auto;
    }
    .book-desc {
        display: block;
    }
    .section {

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