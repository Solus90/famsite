<template>
  <div class="text-gray-900">

    <!-- Header & Navigation -->
    <header class="flex flex-col md:flex-row items-center justify-between text-center">
      <strong>
        <a href="/">
        <img src="/assets/images/fambanner.png" alt="FAM" style="width: 300px;" class="mx-4 md:pt-4">
        </a>
      </strong>
      <nav class="mx-4 flex gap-x-4 text-gray-600">
        <g-link class="nav__link" to="/">Home</g-link>
        <g-link class="nav__link" to="/about-us/">About Us</g-link>
        <g-link class="nav__link" to="/blog/">Blog</g-link>
      </nav>
    </header>

    <!-- Page Content -->
    <main class="">
      <slot/>
    </main>

    
<footer class="p-4 bg-gray-800 shadow md:px-6 md:py-8 dark:bg-gray-900">
    <div class="sm:flex sm:items-center sm:justify-between">
        <a href="https://forallmanakind.com/" class="flex items-center mb-4 sm:mb-0">
            <img src="/assets/images/manabottle.png" class="mr-3 h-8" alt="FAM Logo">
            <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white text-white">ForAllManakind</span>
        </a>
        <ul class="flex flex-wrap items-center mb-6 text-sm text-gray-500 sm:mb-0 dark:text-gray-400">
            <li class="md:mx-2">
                <a href="https://twitter.com/ForAllManakind" class="mr-4 hover:underline md:mr-6" target="_blank">
                  <img src="/assets/images/icons8-twitter-50.png" alt="">
                </a>
            </li>
            <li class="md:mx-2">
                <a href="https://www.twitch.tv/forallmanakind" class="mr-4 hover:underline md:mr-6" target="_blank">
                  <img src="/assets/images/icons8-twitch-50.png" alt=""></a>
            </li>
            <li class="md:mx-2">
                <a href="https://www.tiktok.com/@forallmanakind" class="mr-4 hover:underline md:mr-6" target="_blank">
                  <img src="/assets/images/icons8-tiktok-50.png" alt="">
                </a>
            </li>
            <li class="md:mx-2">
                <a href="https://www.instagram.com/forallmanakind/" class="mr-4 hover:underline md:mr-6" target="_blank">
                  <img src="/assets/images/icons8-instagram-50.png" alt="">
                </a>
            </li>
            <li class="md:mx-2">
                <a href="https://discord.com/invite/c29SY9U" class="mr-4 hover:underline md:mr-6" target="_blank">
                  <img src="/assets/images/icons8-discord-new-50.png" alt="">
                </a>
            </li>
            <li class="md:mx-2">
                <a href="mailto:FAM@forallmanakind.com" class="mr-4 hover:underline md:mr-6" target="_blank">
                  <img src="/assets/images/icons8-open-envelope-50.png" alt="">
                </a>
            </li>
        </ul>
    </div>
    <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8">
    <span class="block text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2022 <a href="https://forallmanakind.com/" class="hover:underline">ForAllManakind™</a>. All Rights Reserved.
    </span>
</footer>


  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style scoped>
/* Add any Global Styles Here */

.active--exact { /* Active Nav Link */
  @apply text-white;
}

footer a:hover img{
  transform: scale(1.1);
}

</style>