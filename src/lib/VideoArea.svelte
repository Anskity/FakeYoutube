<script lang="ts">
    import VideoCard from "./VideoCard.svelte";

    const cardIterator = Array(14);
</script>

<div class="video-area">
    {#each cardIterator as _}
        <VideoCard />
    {/each}
</div>

<style>
    .video-area {
        display: grid;
        padding: 0.5em;
        width: calc(100% - 0.5em * 2);
        height: calc(100% - 0.5em * 2);
        background-color: darkblue;
        gap: 1rem;
        grid-template-columns: repeat(auto-fit, minmax(10.7em, 1fr));
        overflow: clip;
    }
</style>
