<template>
  <div>
    <div class="w-full relative">
      <img src="https://res.cloudinary.com/duveipeci/image/upload/v1602512643/profile-image.jpg" class="object-cover" alt="">
      <div class="flex md:h-12 mt-2 px-1 justify-between">
        <div class="w-16 h-16 md:h-40 md:w-40 top-1/2 bottom-0 relative left-1/12 md:top-neg70">
            <img src="https://res.cloudinary.com/duveipeci/image/upload/v1602514285/profile-photo.jpg" class="rounded-full border-4 border-gray-900 object-cover" alt="">
        </div>
        <div class="md:w-3/12">
          <p class="mb-0 p-2 border sm:text-xs md:text-sm font-bold border-blue-600 rounded-full text-blue-600 hover:cursor-pointer">Edit Profile</p>
        </div>
      </div>
    </div>
    <div class="relative md:mt-10 justify-between">
      <div class="w-full text-left px-4 md:px-8">
        <p class="mb-0">
          <span class="font-bold text-lg">d-artisan</span>
        </p>
        <p class="mb-1">
          <span class="text-gray-500">@ChieduBakwenye</span>
        </p>
        <p>
          <span>
            *any Combo that has [laravel|php|react|vue] fine by me*
          </span>
        </p>
      </div>
    </div>
    <ul class="flex flex-wrap px-4 md:px-8">
      <li class="mr-2">
        <span class="text-gray-500">
          <i class="fas fa-map-marker-alt"></i>
          Nigeria
        </span>
      </li>
      <li class="mr-2">
        <span class="text-gray-500">
          <i class="fas fa-fire-alt"></i>
          Born September 19, 1997
        </span>
      </li>
      <li class="mr-2">
        <span class="text-gray-500">
          <i class="fas fa-calendar-alt"></i>
          Joined January,2018
        </span>
      </li>
    </ul>
    <ul class="flex justify-between px-4 md:px-8 md:w-5/12">
      <li class="text-gray-500">
        <span class="font-bold text-white">
          205
        </span>
        Following
      </li>
      <li class="text-gray-500">
        <span class="font-bold text-white">
          80
        </span>
        Followers
      </li>
    </ul>
    <ul class="flex w-full border-b items-stretch border-gray-800 sm:overflow-auto">
      <li class="text-gray-500 text-center w-4/12  md:w-3/12 py-4 md:hover:bg-blue-900 border-b-2 border-blue-600">
        <span class="font-bold text-blue-600">
          Tweets
        </span>
      </li>
      <li class="text-gray-500 text-center w-8/12 md:w-3/12 py-4 md:hover:bg-blue-900">
        <span class="font-bold">
          Tweets & Replies
        </span>
      </li>
      <li class="text-gray-500 hidden md:block text-center md:w-3/12 py-4 md:hover:bg-blue-900">
        <span class="font-bold">
          Media
        </span>
      </li>
      <li class="text-gray-500 hidden md:block text-center md:w-3/12 py-4 md:hover:bg-blue-900">
        <span class="font-bold">
          Likes
        </span>
      </li>
    </ul>
  </div>
</template>
<script>
export default {

}
</script>