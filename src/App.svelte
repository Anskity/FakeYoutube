<script lang="ts">
    import Header from "./lib/Header.svelte";
    import Navbar from "./lib/Navbar.svelte";
    import VideoArea from "./lib/VideoArea.svelte";
</script>

<Navbar />
<main class="main">
    <Header />
    <VideoArea />
</main>

<style>
    .main {
        margin-left: 5em;
        width: calc(100vw - 5em);
        transform: translateY(-100vh);
    }
</style>
