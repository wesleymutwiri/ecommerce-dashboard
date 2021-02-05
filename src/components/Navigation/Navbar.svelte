<script>
    // import SearchButton from '../SearchButton.svelte';
    export let heading = "Dashboard";
    export let username = "Wesley Mochiemo"
</script>
<nav>
    <div class="navbar">
        <div class="navbar-title">
            <h1>{heading}</h1>
        </div>
        <div class="navbar-content">
            <div class="navbar-icons">
                <div class="icon">
                    <svg viewBox="0 0 24 24" width="24" height="24" stroke="currentColor" stroke-width="2" fill="none"
                        stroke-linecap="round" stroke-linejoin="round" class="css-i6dzq1">
                        <circle cx="11" cy="11" r="8"></circle>
                        <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                    </svg>
                </div>
                <div class="icon">
                    <svg viewBox="0 0 24 24" width="24" height="24" stroke="currentColor" stroke-width="2" fill="none"
                        stroke-linecap="round" stroke-linejoin="round" class="css-i6dzq1">
                        <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
                        <polyline points="22,6 12,13 2,6"></polyline>
                    </svg>
                </div>
                <div class="icon">
                    <svg viewBox="0 0 24 24" width="24" height="24" stroke="currentColor" stroke-width="2" fill="none"
                        stroke-linecap="round" stroke-linejoin="round" class="css-i6dzq1">
                        <path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"></path>
                        <path d="M13.73 21a2 2 0 0 1-3.46 0"></path>
                    </svg>
                </div>
            </div>
            <div class="username">
                <p>{username}</p>
                <div class="avatar">
                    <img src="https://randomuser.me/api/portraits/men/44.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
</nav>

<style>
    .navbar {
        display: flex;
        justify-content: space-between;
        height: 100px;
        align-items: center;
        padding: 10px;
        margin-bottom: 20px;
    }

    .navbar-content {
        display: flex;
        justify-content: space-around;
    }

    .navbar-icons {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .icon {
        padding: 0px 15px;
        cursor: pointer;
    }

    .username {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px;
    }

    .avatar {
        padding: 0px 20px;
    }

    .avatar img {
        border-radius: 50%;
        height: 50px;
    }

    .navbar-title h1 {
        font-weight: lighter;
        padding: 0px 20px;
    }

    @media screen and (max-width: 560px){
        .username p {
            display: none;
        }
        .navbar {
            padding: 0;
            justify-content: flex-start;
        }
        .avatar {
            padding: 0;
        }
        .icon {
            padding: 0px 10px;
        }
        .username {
            padding: 0;
        }
        .navbar-title h1{
            padding: 0;
        }
    }
</style>