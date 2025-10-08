<script>
     let { data } = $props();
</script>

<h2>My Blog Contents Page</h2>

<nav>
    {#each data.posts as post}
        <a href="/blog/{post.title}">{post.title}</a>
    {/each}
</nav>

<style>
    nav{
        display: flex;
        flex-direction: column;
    }
</style>