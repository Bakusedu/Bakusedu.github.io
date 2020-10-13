<template>
  <div class="bg-gray-900 min-h-screen text-white">
    <div class="flex m-0">
      <div class="sm:w-2/12 md:w-2/12">
        <Sidebar/>
      </div>
      <div class="sm:w-full md:w-6/12">
        <ProfileTweet/>
      </div>
      <div class="sm:w-full md:w-4/12">
        <ProfileActivity/>
      </div>
    </div>
  </div>
</template>

<script>
import Sidebar from './SidebarComponent/Sidebar.vue'
import ProfileTweet from './ProfileTweetsComponent/ProfileTweet.vue'
import ProfileActivity from './ProfileActivityComponent/ProfileActivity.vue'
export default {
  name: 'Dashboard',
  components: {
    Sidebar,ProfileTweet,ProfileActivity
  }
}
</script>
