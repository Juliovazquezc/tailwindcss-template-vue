<template>
  <div>
    <div class="container mx-auto py-10">
      <div
        class="border m-6 bg-white mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden"
      >
        <div class="sm:flex sm:items-center px-6 py-4">
          <img
            class="block h-36 rounded-full mx-auto mb-4 sm:mb-0 sm:mr-4 sm:ml-0"
            src="https://avatars.githubusercontent.com/u/43428762?v=4"
            alt="Profile pic"
          />
          <div class="text-center sm:text-left sm:flex-grow">
            <div class="mb-4">
              <p class="text-xl leading-tight">{{ name }} </p>
              <p class="text-sm leading-tight text-grey-dark">
                {{ position }}
              </p>
            </div>
            <div class="flex flex-wrap justify-center sm:justify-start">
              <button
                class="text-xs font-semibold rounded-full px-4 py-1 mr-3 leading-normal bg-white border border-blue text-blue hover:bg-blue hover:text-white"
              >
                Call
              </button>
              <button
                class="text-xs font-semibold rounded-full px-4 py-1 leading-normal bg-white border border-purple text-purple hover:bg-purple hover:text-white"
              >
                Message
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props:{
    name: String,
    position: String,
  },
  name: "Tailwindcss",
};
</script>
