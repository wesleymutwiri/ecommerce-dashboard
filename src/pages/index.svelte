<script>
    import { metatags } from '@roxi/routify';
    import Header from "../components/Header.svelte";
    import RecruitmentProgress from "../components/RecruitmentProgress.svelte";
    import Bio from '../components/Bio.svelte';
    import Calendar from '../components/Calendar.svelte';
    // metatags.title = 'My Routify app'
    // metatags.description = 'Description coming soon...'
</script>

<div class="container">
    <div class="dashboard-content">
        <Header />

        <RecruitmentProgress />

    </div>
    <div class="calendar-and-events">
        <div class="calendar">
            <Calendar /> 
            
        </div>
        <div class="bio">
            <Bio />
        </div>
    </div>
</div>

<style>
    .container {
        display: grid;
        grid-template-areas: "content content events";
    }

    .dashboard-content {
        grid-area: content;
        padding: 0px 30px;
    }

    .calendar-and-events {
        grid-area: events;
        padding: 0px 30px;
    }

    @media screen and (max-width: 1400px) {
        .container {
            display: flex;
            flex-direction: column;
        }
    }
</style>