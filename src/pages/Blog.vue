<template>
  <Layout>
    <div class="hero-image -mt-24 p-8">
      <div class="mx-4 md:mx-20 mt-48">
        <h1 class="text-4xl mb-2 text-white">Welcome to your Blog!</h1>

        <div class="space-y-4">
          <BlogFeedPost
            v-for="edge in $page.allPost.edges"
            :key="edge.node.id"
            :post="edge.node"
          />
        </div>
      </div>
    </div>
  </Layout>
</template>

<page-query>
query {
  allPost {
    edges {
      node {
        id
        title
        date (format: "D MMMM YYYY")
        path
        description
      }
    }
  }
}
</page-query>

<script>
import BlogFeedPost from "@/components/BlogFeedPost";

export default {
  components: {
    BlogFeedPost,
  },
  metaInfo: {
    title: "Blog",
  },
};
</script>

<style scoped>
.hero-image {
  background-image: url("/assets/images/fambg.jpg"); /* The image used */
  background-color: #cccccc; /* Used if the image is unavailable */
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: cover; /* Resize the background image to cover the entire container */
}
</style>
