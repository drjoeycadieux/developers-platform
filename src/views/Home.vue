<template>
  <div class="bg-gray-700 p-12">
    <div class="container mx-auto py-10 px-2">
      <div class="w-full text-center">
        <h1 class="text-white uppercase">
          UI Design - UX Design - Web Developer - Software Engineer
        </h1>
      </div>
    </div>

    <!-- Section 2 -->

    <div class="container mx-auto py-auto py-10 px-2">
      <div class="text-white text-center font-bold">
        <h2 class="text-white text-center text-3xl font-bold">
          Popular Topics
        </h2>
      </div>
    </div>

    <!-- Section 3 -->

    <div class="bg-gray-700 p-12">
      <div class="container mx-auto py-10 px-2">
        <h2 class="text-white text-center font-bold">
          The union denounces the federal bill against the strike at the Port of
          Montreal - April 29, 2021
        </h2>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="column">
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/jyAyPghd020?controls=0"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </div>

    <!-- UI Components -->

    <!-- <div class="min-h-screen bg-gray-200 flex justify-center items-center">
      <div
        class="max-w-2xl bg-white border-2 border-gray-300 p-5 rounded-md tracking-wide shadow-lg"
      >
        <div id="header" class="flex">
          <img
            alt="mountain"
            class="w-45 rounded-md border-2 border-gray-300"
            src="https://picsum.photos/seed/picsum/200"
          />
          <div id="body" class="flex flex-col ml-5">
            <h4 id="name" class="text-xl font-semibold mb-2">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit
            </h4>
            <p id="job" class="text-gray-800 mt-2">
              Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
            <div class="flex mt-5">
              <img
                alt="avatar"
                class="w-6 rounded-full border-2 border-gray-300"
                src="https://picsum.photos/seed/picsum/200"
              />
              <p class="ml-3">John Doe</p>
            </div>
          </div>
        </div>
      </div> -->

    <!-- End UI Components -->

    <!-- <div class="flex-1 bg-black border-b-2 border-grey-darkest pt-5">
      <div class="container mx-auto text-center text-white">
        <h4 class="uppercase">As seen on these media networks</h4>
      </div>

      <div
        class="flex flex-wrap item-center container mx-auto justify-center py-4"
      >
        <img
          class="h-16 filter-grayscale mx-4 my-4 grow"
          src="./assets/gma.png"
        />
        <img
          class="h-16 filter-grayscale mx-4 my-4 grow"
          src="./assets/today.png"
        />
        <img
          class="h-16 filter-grayscale mx-4 my-4 grow"
          src="./assets/cnn.png"
        />
        <img
          class="h-16 filter-grayscale mx-4 my-4 grow"
          src="./assets/fox.png"
        />
        <img
          class="h-16 filter-grayscale mx-4 my-4 grow"
          src="./assets/nbc.png"
        />
        <img
          class="h-16 filter-grayscale mx-4 my-4 grow"
          src="./assets/sinclair.png"
        />
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  props: ["text"],
};
</script>