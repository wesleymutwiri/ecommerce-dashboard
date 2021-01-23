<script>
    export let name = "Wesley"
    export let notification_number = 9;
</script>
<div class="container">
    <div class="text">
        <h2>Hello {name}!</h2>
        <p>Today you have {notification_number} notifications</p>
        <p>Also, you need to hire ROR developer, Svelte. JS <br> Developer</p>
    </div>
    <div class="image">
        <img src="/celebration.svg" alt="">
    </div>
</div>

<style>
    h2 {
        font-family: 'Nunito', sans-serif;
    }
    .container {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        background: #ed960b;
        border-radius: 30px;
        padding: 30px;
        width: 100%;
    }
    .image {
        width: 30%;
    }
    img {
        width: 100%;
    }
</style>