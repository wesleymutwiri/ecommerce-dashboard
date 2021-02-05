<script>
    import { isActive, url } from '@roxi/routify';
</script>
<div class="sidebar">
  <div class="sidebar-links">
      <ul class="sidebar-items">
        <li class="sidebar-link logo">
            <img src="/fox-svg.svg" alt="">
            <h2> <a href="">FoxHR</a></h2>
        </li>
      <li class="sidebar-link active">
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
        >
          <rect x="3" y="3" width="7" height="7"></rect>
          <rect x="14" y="3" width="7" height="7"></rect>
          <rect x="14" y="14" width="7" height="7"></rect>
          <rect x="3" y="14" width="7" height="7"></rect>
        </svg>
        <a href="" >Dashboard</a>
      </li>
      <li class="sidebar-link">
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
        >
          <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path>
          <circle cx="9" cy="7" r="4"></circle>
          <path d="M23 21v-2a4 4 0 0 0-3-3.87"></path>
          <path d="M16 3.13a4 4 0 0 1 0 7.75"></path>
        </svg>
        <a href="">Recruitment</a>
      </li>
      <li class="sidebar-link">
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
        >
          <path
            d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"
          ></path>
          <polyline points="14 2 14 8 20 8"></polyline>
          <line x1="16" y1="13" x2="8" y2="13"></line>
          <line x1="16" y1="17" x2="8" y2="17"></line>
          <polyline points="10 9 9 9 8 9"></polyline>
        </svg>
        <a href="">Onboarding</a>
      </li>
      <li class="sidebar-link">
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
        >
          <path d="M21.21 15.89A10 10 0 1 1 8 2.83"></path>
          <path d="M22 12A10 10 0 0 0 12 2v10z"></path>
        </svg>
        <a href="">Reports</a>
      </li>
      <li class="sidebar-link">
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
        >
          <rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect>
          <line x1="16" y1="2" x2="16" y2="6"></line>
          <line x1="8" y1="2" x2="8" y2="6"></line>
          <line x1="3" y1="10" x2="21" y2="10"></line>
        </svg>
        <a href=""> Calendar </a>
      </li>
      <li class="sidebar-link">
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
        >
          <circle cx="12" cy="12" r="3"></circle>
          <path
            d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0 0-1.51 1z"
          ></path>
        </svg>
        <a href="#"> Settings </a>
      </li>
    </ul>
  </div>
  <div class="sidebar-message">
    <h4>Use our Premium <br> Features Now!</h4>
        <div class="premium-image">
       <div class="custom-shape-divider-top-1611431706">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M985.66,92.83C906.67,72,823.78,31,743.84,14.19c-82.26-17.34-168.06-16.33-250.45.39-57.84,11.73-114,31.07-172,41.86A600.21,600.21,0,0,1,0,27.35V120H1200V95.8C1132.19,118.92,1055.71,111.31,985.66,92.83Z" class="shape-fill"></path>
    </svg>
</div>
            <img src="/Celebration-amico.svg" alt="" />
        </div>
  </div>
</div>

<style>
  .sidebar {
    max-width: 300px;
    width: 100%;
    /* min-height: 100vh; */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    background-color: #262125;
    color: #fff;
    max-height: 100vh;
  }
  img {
    width: 100%;
  }

  .sidebar-link.logo {
    padding: 40px;
  }

  .logo h2 a{
    font-weight: 900;
  }

  .logo img {
    width: 70px;
    color: white;
    margin-right: 20px;
  }

  h4 {
    margin: 20px 15px;
    padding: 10px 25px;
  }

  .sidebar-link {
    display: flex;
    align-items: center;
    justify-items: center;
    padding: 10px 25px;
  }
  .sidebar-link svg {
    margin: 18px;
  }
  .premium-image {
    position: relative;
    width: 100%;
    background: #e2d9c8;
    /* clip-path: url('/wave.svg'); */
  }

  .active {
    color: #ed960b;
    border-right: 5px solid #ed960b;
  }

  .active a {
    color: #ed960b;
  }
  .sidebar-message {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  /* .premium-image::before {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    top: 0;
    width: 100%;
    height: 600px;
    background: url('wave.svg');
    background-repeat: no-repeat;
    -webkit-background-size: 100% 100%;
    background-size: cover;
    background-position: center;
    height: 100%;
  } */
  .custom-shape-divider-top-1611431706 {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
    transform: rotate(180deg);
}

.custom-shape-divider-top-1611431706 svg {
    position: relative;
    display: block;
    width: calc(100% + 0.5px);
    height: 40px;
    transform: rotateY(180deg);
}

.custom-shape-divider-top-1611431706 .shape-fill {
    fill: #262125;
}
@media screen and (max-width: 1200px){
    .sidebar {
        display: none;
    }
}
</style>
