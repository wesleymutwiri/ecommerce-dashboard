<script>
    import { metatags } from '@roxi/routify';
    import Header from "../components/Header.svelte";
    // metatags.title = 'My Routify app'
    // metatags.description = 'Description coming soon...'
</script>

<div class="container">
    <div class="dashboard-content">
        <Header />
    </div>
    <div class="calendar-and-events">
        calendar 
        events
    </div>
</div>

<style>
    .container  {
        display: grid;
        grid-template-areas: "content content events";
    }
    .dashboard-content {
        grid-area: content;
    }
    .calendar-and-events {
        grid-area: events;
    }

</style>