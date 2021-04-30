<template>
  <div class="w-full">
    <div
      class="flex flex-wrap w-full font-bold bg-gray-300 rounded shadow-md mb-6"
    >
      <div class="px-6 py-4 w-full md:w-auto -mb-3 md:mb-0">Quick Actions</div>
      <div class="flex-1 text-left py-3 px-4 w-full md:w-auto md:text-right">
        <router-link
          tag="button"
          to="/admin/tools/email-generator"
          class="bg-blue-700 text-white rounded px-2 py-1 md:ml-3 ml-0 mr-3 md:mr-0 mt-3 md:mt-0"
        >
          Email Generator
        </router-link>
        <router-link
          tag="button"
          to="/admin/tools/announcements"
          class="bg-blue-700 text-white rounded px-2 py-1 md:ml-3 ml-0 mr-3 md:mr-0 mt-3 md:mt-0"
        >
          Announcement Generator
        </router-link>
        <router-link
          tag="button"
          to="/admin/sales/pending"
          class="bg-blue-700 text-white rounded px-2 py-1 md:ml-3 ml-0 mr-3 md:mr-0 mt-3 md:mt-0"
        >
          Pending Sales
        </router-link>
        <router-link
          tag="button"
          to="/admin/sales/processing"
          class="bg-blue-700 text-white rounded px-2 py-1 md:ml-3 ml-0 mr-3 md:mr-0 mt-3 md:mt-0"
        >
          Processing Sales
        </router-link>
        <router-link
          tag="button"
          to="/media/latest"
          class="bg-blue-700 text-white rounded px-2 py-1 md:ml-3 ml-0 mr-3 md:mr-0 mt-3 md:mt-0"
        >
          Media Panel
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dashboard",
};
</script>