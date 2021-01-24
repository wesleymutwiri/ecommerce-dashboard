<div class="bio">
    <div class="bio-header">
        <div class="avatar">
            <img src="https://randomuser.me/api/portraits/men/44.jpg" alt="">
        </div>
        <div class="name-and-tag">
            <h3>Wesley Mochiemo</h3>
            <p class="lighter">Sr. Fullstack Developer</p>
        </div>
        <div class="menu">
            elipsis
        </div>
    </div>
    <div class="contact-details">
        some icons
        some icons
        some icons
    </div>
    <div class="bio-body">
        <div class="row">
            <div class="bio-name">
                Company
            </div>
            <div class="bio-description">
                Something
            </div>
        </div>
        <div class="row">
            <div class="bio-name">
                ANother
            </div>
            <div class="bio-description">
                one
            </div>
        </div>
        <div class="row">
            <div class="bio-name">
                Another
            </div>
            <div class="bio-description">
                one
            </div>

        </div>
    </div>
</div>

<style>
    .bio {
        background-color: #fff;
        border-radius: 20px;
        padding: 30px;
        min-width: 400px;
    }

    .bio-header {
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .avatar img {
        border-radius: 50%;
        height: 80px;
        width: 80px;
    }

    .name-and-tag {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    h3 {
        padding: 10px 0px;
    }

    .name-and-tag p {
        color: rgba(0, 0, 0, 0.384);
    }

    .contact-details {
        display: flex;
    }

    .bio-body {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .row {
        display: flex;
        align-items: baseline;
        padding: 10px 0px;
        justify-content: space-between;
    }

    .bio-description {
        width: 50%;
        padding: 0px 20px;
        color: rgba(0, 0, 0, 0.493);

    }

    .bio-name {
        width: 50%;
    }
</style>