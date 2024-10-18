<template>
  <div class="min-h-[100vh] bg-gray-400 relative">
    <img src="@/assets/AirBalloon.avif" class="absolute inset-0 h-full w-full object-cover z-0 opacity-20" alt="Air Balloon">
    <div class="flex flex-col justify-center items-center h-screen z-10 relative">
      <!-- <h1 class="text-2xl text-white">Resume Maker</h1> -->
      <form action="" class="bg-white p-5 rounded-md flex flex-col gap-y-3 shadow-md">
        <h1 class="text-xl">Personal Detail</h1>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-y-2 gap-x-2">
          <label for="first-name" class="sr-only">First Name</label>
          <input id="first-name" type="text" class="border rounded-md bg-gray-50 px-2 p-1" placeholder="First Name" />
          
          <label for="last-name" class="sr-only">Last Name</label>
          <input id="last-name" type="text" class="border rounded-md bg-gray-50 px-2 p-1" placeholder="Last Name" />
          
          <label for="email" class="sr-only">Email</label>
          <input id="email" type="email" class="border rounded-md bg-gray-50 px-2 p-1" placeholder="eg@email.com" />
          
          <label for="phone" class="sr-only">Phone</label>
          <input id="phone" type="tel" class="border rounded-md bg-gray-50 px-2 p-1" placeholder="+91 9876543210" />
        </div>
        <button type="submit" class="flex justify-center bg-blue-500 p-1 text-white rounded-md hover:bg-blue-600 transition">Next</button>
      </form>
    </div>
  </div>
</template>


<script>
// @ is an alias to /src

export default {
  name: "HomeView",
};
</script>
