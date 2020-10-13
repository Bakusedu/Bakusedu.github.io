<template>
  <div class="border-r border-gray-800 min-h-screen">
    <ProfileHeader/>
    <ProfileUser/>
  </div>
</template>

<script>
import ProfileHeader from './ProfileHeaderComponent/ProfileHeader.vue'
import ProfileUser from './ProfileUserComponent/ProfileUser.vue'
export default {
    name: 'ProfileTweet',
    components: {
        ProfileHeader,
        ProfileUser
  }
}
</script>

<style>

</style>