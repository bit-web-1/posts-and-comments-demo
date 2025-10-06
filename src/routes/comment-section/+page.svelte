<script>
    import Comment from '$lib/components/Comment.svelte';
    let { data } = $props(); // important: comes from the load function - has to be called data
</script>

{#each data.comments as comment}
    <Comment data={comment} />
{/each}