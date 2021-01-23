<!-- routify:options preload="proximity" -->
<script>
import Sidebar from '../components/Sidebar.svelte';
</script>
<div class="container">
    <Sidebar />
    <main>
        <slot />
    </main>
</div>
<style>
.container {
    display: flex;
    background: #262125;
}
main {
    border-radius: 40px 0px 0px 0px ;
    background: #eee;
    width: 100%;
    height: 100%;
    min-height: 100vh;
    padding: 30px 20px;
}
</style>
