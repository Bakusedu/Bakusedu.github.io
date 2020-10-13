<template>
  <div class="px-8 py-4 hidden md:block">
      <div class="w-full">
          <div class="relative mb-3">
            <span class="block absolute top-1/4 left-2/12 text-gray-500">
                <i class="fas fa-search"></i>
            </span>
            <input type="text" class="rounded-full bg-blue-900 h-12 w-full pl-12" placeholder="Search Twitter">
          </div>
          <div class="bg-blue-900 rounded-lg mb-3">
            <div class="p-4 border-b border-gray-800">
              <h4 class="font-bold text-left">You might like</h4>
            </div>
            <div class="flex p-2 border-b border-gray-800">
              <div class="w-2/12">
                <img src="https://res.cloudinary.com/duveipeci/image/upload/v1602514285/profile-photo.jpg" class="rounded-full h-16 w-16" alt="">
              </div>
              <div class="w-6/12 text-left pl-2">
                <p class="font-bold">developer_ed</p>
                <p class="text-gray-500">@_nedu</p>
              </div>
              <div class="w-4/12">
                <p class="p-2 rounded-full border border-blue-600 text-blue-600">Follow</p>
              </div>
            </div>
            <div class="flex p-2 border-b border-gray-800">
              <div class="w-2/12">
                <img src="https://res.cloudinary.com/duveipeci/image/upload/v1602514285/profile-photo.jpg" class="rounded-full h-16 w-16" alt="">
              </div>
              <div class="w-6/12 text-left pl-2">
                <p class="font-bold">developer_ed</p>
                <p class="text-gray-500">@_nedu</p>
              </div>
              <div class="w-4/12">
                <p class="p-2 rounded-full border border-blue-600 text-blue-600">Follow</p>
              </div>
            </div>
            <div class="flex p-2">
              <div>
                <p class="p-2 font-bold text-blue-600">Show more</p>
              </div>
            </div>
          </div>
          <div class="bg-blue-900 rounded-lg mb-3">
            <div class="p-4 border-b flex justify-between border-gray-800">
              <h4 class="font-bold text-left">Trends for you</h4>
              <span class="text-blue-600 block">
                <i class="fas fa-cog"></i>
              </span>
            </div>
            <div class="flex p-4 justify-between border-b border-gray-800">
              <h4 class="text-left">Yabaleft</h4>
              <span class="block">
                <i class="fas fa-chevron-down"></i>
              </span>
            </div>
            <div class="flex p-2">
              <div>
                <p class="p-2 font-bold text-blue-600">Show more</p>
              </div>
            </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>