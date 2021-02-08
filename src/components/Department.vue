<template>
  <div class="h-screen w-screen bg-gray-100  flex flex-col ">
   

     <div
      class="bg-white border-black rounded shadow  w-1/2 "
    >
     
        <div class="p-8 flex flex-wrap justify-start">
          <label for="name" class=" w-full  text-left">Department</label>
          <input type="text" id="name" class="p-2 w-full border-2" />
        </div>
        <div
          class="px-8 py-4 bg-gray-100 border-t border-gray-200 flex justify-end"
        >
          <button class="bg-indigo-800 text-white p-2 rounded-md" type="submit">
            Create Department
          </button>
        </div>
    
    </div>

  </div>
</template>

<script>
export default {
  data() {
    return {
      sending: false,
      form: {
        name: null,
      },
    };
  },
};
</script>

<style>
</style>