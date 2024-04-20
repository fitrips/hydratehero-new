<template>
  <!-- component -->
  <div class="flex items-center h-screen w-full justify-center">
    <div class="max-w-xs relative">
      <!-- Shadow -->
      <div class="absolute top-0 left-0 w-full h-full rounded-lg shadow-lg z-0"></div>
      <!-- Card -->
      <div class="bg-white rounded-lg overflow-hidden shadow-xl relative z-10">
        <div class="photo-wrapper p-2">
          <img class="w-32 h-32 rounded-full mx-auto" src="https://www.gravatar.com/avatar/2acfb745ecf9d4dccb3364752d17f65f?s=260&d=mp" alt="John Doe">
        </div>
        <div class="p-2">
          <h3 class="text-center text-xl text-gray-900 font-medium leading-8">John Doe</h3>
          <div class="text-center text-gray-400 text-xs font-semibold">
            <p>Web Developer</p>
          </div>
          <table class="text-xs my-3">
            <tbody>
              <tr>
                <td class="px-2 py-2 text-gray-500 font-semibold">Address</td>
                <td class="px-2 py-2">Chatakpur-3, Dhangadhi Kailali</td>
              </tr>
              <tr>
                <td class="px-2 py-2 text-gray-500 font-semibold">Phone</td>
                <td class="px-2 py-2">+977 9955221114</td>
              </tr>
              <tr>
                <td class="px-2 py-2 text-gray-500 font-semibold">Email</td>
                <td class="px-2 py-2">john@example.com</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>
