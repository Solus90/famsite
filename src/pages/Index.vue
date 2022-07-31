<template>
  <Layout>
    <div class="hero-image -mt-24 p-8">
      <div class="mx-4 md:mx-20 mt-48 md:grid md:grid-cols-2 md:gap-8">
        <!-- <img src="/assets/images/thefam.jpeg" style="rounded" /> -->
        <iframe
    src="https://player.twitch.tv/?channel=forallmanakind&parent=localhost&muted=true"
    height="360"
    width="100%"
    allowfullscreen>
</iframe>

        <div class="blurb mx-2">
          <p class="text-white">
            For All Manakind is a group of three content creators, Tim, Trey,
            and Trevor, based out of Ohio. They have been creating gaming
            content on Twitch and YouTube since February 2017 and received
            Twitch affiliate status in June of 2017. Having three different
            content creators allows for a wide variety of content unique to each
            member, as well as collaboration. This includes live streams, game
            reviews, community game nights, tournaments, and more. Community is
            their focus, including curating a welcome, safe space for
            like-minded gamers, and working with other streamers, game
            developers, brands, and charities.
          </p>
        </div>
        <!-- <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/InYdKmB1WXg"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe> -->
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home",
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