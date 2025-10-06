<script>
    let { postData } = $props();
</script>

<section>
    <header>
        <img src="{postData.avatar}" alt="{postData.username}">
        <h3>{postData.username}</h3>
    </header>
    <main>
        <p>{postData.postText}</p>
    </main>
    <footer>
        <p>{postData.postDate}</p>
        <p>👍 {postData.likes}</p>
    </footer>
</section>

<style>
    section {
        border: 1px solid #ccc;
        background-color: #eee;
        border-radius: 0.8em;
        padding: 1em;
        margin-bottom: 1em;
    }
    header {
        display: flex;
    }
    img {
        max-width: 3rem;
        margin: 10px 15px 15px 10px;
    }
    h3 {
        margin-top: 1.5rem;
    }
    main {
        margin-top: 1em;
    }
</style>