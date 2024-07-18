<script lang="ts">
    const home_icon_url =
        "https://th.bing.com/th/id/R.de83047316301298e2329b45c992a6b3?rik=vUAIk6o9y5aa3A&pid=ImgRaw&r=0";
    const ytshorts_icon_url =
        "https://upload.wikimedia.chinapedia.org/wikipedia/commons/thumb/f/fc/Youtube_shorts_icon.svg/800px-Youtube_shorts_icon.svg.png";
</script>

<div class="navbar">
    <a href={"#"}><img src={home_icon_url} alt="Home" /></a>
    <a href={"#"}><img src={ytshorts_icon_url} alt="Youtube Shorts" /></a>
</div>

<style>
    .navbar {
        display: flex;
        flex-direction: column;
        width: calc(5em - 1em * 2);
        height: calc(100vh - 1em * 2);
        overflow: clip;
        background-color: green;
        gap: 0;
        padding: 1em;
    }
    .navbar a {
        margin: 0;
        width: 1fr;
    }
    .navbar a img {
        margin: 0;
        width: 100%;
        height: 100%;
    }
</style>
