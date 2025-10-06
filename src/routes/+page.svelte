<script>
    import Post from '$lib/components/Post.svelte';
    let posts = [
    {
        username: "jane_doe",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-01",
        postText: "Loving the crisp autumn air 🍂",
        likes: 34
    },
    {
        username: "tech_guy",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-02",
        postText: "Just built my first React app!",
        likes: 89
    },
    {
        username: "nature_lover",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-03",
        postText: "Hiked through the forest today. So peaceful.",
        likes: 56
    },
    {
        username: "foodie_queen",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-04",
        postText: "Pumpkin spice latte season is here 🎃☕",
        likes: 102
    },
    {
        username: "bookworm42",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-05",
        postText: "Just finished reading 'The Midnight Library' — wow!",
        likes: 73
    },
    {
        username: "gamer_x",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-06",
        postText: "Levelled up in Elden Ring today 💪",
        likes: 45
    },
    {
        username: "artist_soul",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-07",
        postText: "New painting finished. Feeling proud 🎨",
        likes: 67
    },
    {
        username: "travel_bug",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-07",
        postText: "Exploring Kyoto was a dream come true 🇯🇵",
        likes: 120
    },
    {
        username: "fitness_freak",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-07",
        postText: "Morning run complete. 10K in the bag 🏃‍♂️",
        likes: 88
    },
    {
        username: "music_maven",
        avatar: "https://avatar.iran.liara.run/public",
        postDate: "2025-10-07",
        postText: "New album dropped today — go listen! 🎧",
        likes: 95
    }
];
</script>

{#each posts as post}
    <Post postData={post} />
{/each}

