<template>
  <div class="bg-gray-800">
    <div
      class="px-5 md:px-0 py-5 container mx-auto flex sm:justify-between justify-start"
    >
      <div class="w-1/2">
        <p class="text-sm text-white">
          Copyright &copy; {{ getYear() }} Powered By
          <a class="text-white font-bold" href="severestormsmedia.com"
            >SevereStormsMedia</a
          >
          Severe Weather Chaser, LLC. All rights reserved.
        </p>
      </div>
      <div class="w-1/2"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterPage",
  methods: {
    getYear() {
      return new Date().getFullYear();
    },
  },
};
</script>