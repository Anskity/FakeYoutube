<script lang="ts">
    import YoutubeLogo from "./YoutubeLogo.svelte";
</script>

<header class="main-header">
    <div class="youtube-logo">
        <YoutubeLogo />
    </div>
    <div class="searchbar">
        <input placeholder="Search..." />
    </div>
</header>

<style>
    .main-header {
        background-color: blue;
        display: flex;
        flex-basis: content;
        flex-direction: row;
        position: relative;
        top: 0;
        margin-top: 0;
        padding: 1em;
        height: 3em;
        gap: 1em;
        width: calc(100% - 1em * 2);
    }

    .main-header .searchbar {
        width: 75%;
        height: 100%;
        display: grid;
        place-items: center;
    }
    .main-header .searchbar input {
        width: 100%;
        height: 70%;
    }
    .youtube-logo {
        width: 0.1fr;
        height: 90%;
        overflow: clip;
    }
</style>
