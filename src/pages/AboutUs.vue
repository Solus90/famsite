<template>
  <Layout>
    <div class="hero-image -mt-24 p-8">
      <div class="grid md:grid-cols-2 md:mx-24 mt-48 gap-12">
        <div class="about text-white">
          <h1 class="">About FAM</h1>
          <p>
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
        <div class="viewership text-white">
          <h1 class="">Viewership</h1>
          <p class="text-xs italic">As of April 4th 2022</p>
          <div class="grid grid-cols-3 mx-auto gap-8">
            <div class="text-center">
              <h1>10</h1>
              <p>Average CCV</p>
            </div>
            <div class="text-center">
              <h1>921</h1>
              <p>Hours Watched</p>
            </div>
            <div class="text-center">
              <h1>46k</h1>
              <p>Lifetime Views</p>
            </div>
            <div class="text-center">
              <h1>427</h1>
              <p>Unique Viewers</p>
            </div>
            <div class="text-center">
              <h1>82</h1>
              <p>Unique Chatters</p>
            </div>
            <div class="text-center">
              <h1>88</h1>
              <p>Average CCV</p>
            </div>
          </div>
        </div>
        <div class="interests text-white">
          <h1>Interests</h1>
          <ul class="list-disc">
            <li>Roleplaying Games</li>
            <li>Horror/Survival Games</li>
            <li>Strategy/Tactics Games</li>
            <li>Indie Games</li>
            <li>Co-op games</li>
            <li>Fighting Games</li>
            <li>Playing with viewers</li>
          </ul>
        </div>
        <div class="achievements text-white">
          <h1>Achievements</h1>
          <ul class="list-disc">
            <li>Extra Life Charity Stream</li>
            <li>St Jude Play Live Charity Stream</li>
            <li>RAICES Charity Stream</li>
            <li>Hosts of the FAM Game Awards</li>
            <li>Hosts of various tournaments</li>
            <li>Hosts of FAMcon (gaming meetup)</li>
            <li>Hosts of the FAMcast podcast</li>
            <li>Travel to industry events</li>
          </ul>
        </div>
      </div>
      <div class="p-4 mx-16">
        <a href="/assets/documents/fammediakit.pdf" target="_blank">
        <button
          class="
            px-4
            py-2
            bg-gray-200
            hover:bg-gray-300
            text-gray-800 text-lg
            font-medium
            rounded-full
          "
        >
          Influencer Deck
        </button>
        </a>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "About Us",
  },
};
</script>

<style>
.hero-image {
  background-image: url("/assets/images/fambg.jpg"); /* The image used */
  background-color: #cccccc; /* Used if the image is unavailable */
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: cover; /* Resize the background image to cover the entire container */
}

h1 {
  font-size: 3rem;
  font-weight: 700;
}

p {
}
</style>