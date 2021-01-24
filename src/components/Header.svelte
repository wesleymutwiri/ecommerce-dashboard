<script>
    export let name = "Wesley"
    export let notification_number = 9;
</script>
<div class="container">
    <div class="text">
        <div class="name">
            <h2>Hello {name}!</h2>
        </div>
        <div class="notification">
            <p>Today you have {notification_number} notifications</p>
            <p>Also, you need to hire ROR developer, Svelte. JS <br> Developer</p>
        </div>

        <a href="#">Read more</a>
    </div>
    <div class="image">
        <img src="/celebration.svg" alt="">
    </div>
</div>

<style>
    h2 {
        /* font-family: 'Nunito', sans-serif; */
        margin: 0.5rem 0px;
    }

    .container {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        background: #ed960b;
        border-radius: 30px;
        padding: 30px;
        width: 100%;
        color: white;
        max-width: 800px;
    }

    .image {
        width: 30%;
    }

    img {
        width: 100%;
    }

    a {
        text-decoration: underline;
        margin-top: 1rem;
    }

    .text {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
</style>