<template>
    <div class="container mx-auto">
        <div class="flex flex-col md:flex-row w-full">
      <div class="md:w-1/2 p-8">
        <img
          src="https://cdn.pixabay.com/photo/2015/11/03/08/58/meeting-1019875_960_720.jpg"
          alt="Contact Us"
          class="w-full h-full object-cover"
        />
      </div>
      <div class="md:w-1/2 p-8 shadow-md">
        <p class="text-lg mb-2">
          123 Main Street <br />
          Ranchi, Pakistan 12345
        </p>
        <p class="text-lg mb-2">
          Phone: (123) 123-123123 <br />
          Email: info@imran.com
        </p>
        <form class="bg-white rounded px-8 pt-6 pb-8 mb-4">
          <div class="mb-4">
            <label for="name" class="block text-gray-700 font-bold mb-2">Name</label>
            <input
              id="name"
              placeholder="Name"
              type="text"
              class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
            />
          </div>
          <div class="mb-4">
            <label for="email" class="block text-gray-700 font-bold mb-2">Email</label>
            <input
              id="email"
              placeholder="Email"
              type="text"
              class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
            />
          </div>
          <div class="mb-4">
            <label for="message" class="block text-gray-700 font-bold mb-2">Message</label>
            <input
              id="message"
              placeholder="Message"
              type="text"
              class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
            />
          </div>
          <div class="flex items-center justify-center mt-6">
            <button
              class="bg-rose-500 hover:bg-rose-700 text-white font-bold py-2 px-8 rounded-full focus:outline-none focus:shadow-outline"
              type="button"
            >
              Submit
            </button>
          </div>
        </form>
      </div>
    </div>
    </div>
  </template>
  
  <script setup>
  </script>
  