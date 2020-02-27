<template>
  <div class="bg-white w-1/2 m-4 rounded-lg shadow p-4 mx-auto text-black
  ">
    <label class="block">
        <span class="text-gray-700">Title</span>
        <input
        v-model="title" class="form-input mt-1 block w-full"  placeholder="My New Note" />
    </label>
    <label class="block mt-4">
      <span class="text-gray-700">Content</span>
      <textarea class="form-textarea mt-1 block w-full" rows="3" placeholder="The content of my new super cool note">
      </textarea>
      </label>
      <div class="buttons w-full flex justify-center">
          <button class="bg-gray-500 hover:bg-gray-700 text-white font-bold py-2 px-4 rounded mt-4 mr-4 flex-grow @click=$router.push('/')">
            Cancel</button>
            <button class="bg-blue-500 hover:bg-gray-700 text-white font-bold py-2 px-4 rounded mt-4 mr-4 flex-grow">
                Add</button>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Form'
}
</script>

<style>

</style>