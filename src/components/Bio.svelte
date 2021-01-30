<div class="bio">
    <div class="bio-header">
        <div class="avatar">
            <img src="https://randomuser.me/api/portraits/men/44.jpg" alt="" />
        </div>
        <div class="name-and-tag">
            <h3>Wesley Mochiemo</h3>
            <p class="lighter">Sr. Fullstack Developer</p>
        </div>
        <div class="menu">
            <svg
                viewBox="0 0 24 24"
                width="24"
                height="24"
                stroke="currentColor"
                stroke-width="2"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="css-i6dzq1"
                ><circle cx="12" cy="12" r="1" /><circle
                    cx="19"
                    cy="12"
                    r="1"
                /><circle cx="5" cy="12" r="1" /></svg
            >
        </div>
    </div>
    <div class="contact-details">
        <div class="icon">
            <svg
                viewBox="0 0 24 24"
                width="24"
                height="24"
                stroke="#fff"
                stroke-width="2"
                fill="black"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="css-i6dzq1"
                ><path
                    d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"
                /></svg
            >
        </div>
        <div class="icon">
            <svg
                viewBox="0 0 24 24"
                width="24"
                height="24"
                stroke="#fff"
                stroke-width="2"
                fill="black"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="css-i6dzq1"
                ><path
                    d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"
                /><polyline points="22,6 12,13 2,6" /></svg
            >
        </div>
        <div class="icon">
            <svg
                viewBox="0 0 24 24"
                width="24"
                height="24"
                stroke="currentColor"
                stroke-width="2"
                fill="black"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="css-i6dzq1"
                ><path
                    d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"
                /></svg
            >
        </div>
    </div>
    <div class="bio-body">
        <div class="row">
            <div class="bio-name">Company</div>
            <div class="bio-description">Something</div>
        </div>
        <div class="row">
            <div class="bio-name">ANother</div>
            <div class="bio-description">one</div>
        </div>
        <div class="row">
            <div class="bio-name">Another</div>
            <div class="bio-description">one</div>
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

    .icon {
        border-radius: 50%;
        display: flex;
        align-items: center;
        padding: 10px; 
        background: #eee;
    }

    .contact-details {
        display: flex;
        justify-content: space-between;
        width: 50%;
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

    .menu {
        cursor: pointer;
    }
</style>
