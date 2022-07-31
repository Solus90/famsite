<template>
    <div>
        <h3 class="text-2xl font-bold" v-html="post.title"/>
        <span class="block text-sm font-bold text-white" v-html="post.date"/>
        <p class="my-2" v-html="post.description"/>
        <g-link :to="post.path"><button class="text-blue-300">Read &rarr;</button></g-link>
    </div>
</template>

<script>
export default {
    name: 'BlogFeedPost',
    props: [
        'post'
    ],
}
</script>