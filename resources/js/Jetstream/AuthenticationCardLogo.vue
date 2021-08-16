<template>
    <Link :href="'/'">
        <p class="text-white font-bold text-3xl"><img class="inline mr-2" src='../img/spotify.png'>Welcome To Spotify Clone</p>
    </Link>
</template>

<script>
    import { Link } from '@inertiajs/inertia-vue3';

    export default {
        components: {
            Link,
        },
    }
</script>
