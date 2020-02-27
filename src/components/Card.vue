<template>
  <div class="bg-white w-1/5 mx-4 mb-4 rounded-lg shadow p-4 text-black  ">
      <h1 class="text-xl text-blue-900">Note Tile</h1>
      <p>Content of the Note</p>
      <div class="flex justify-end text-xs">
          <button class="text-green-500 pr-2">Edit</button>
          <button class="text-red-500">Delete</button>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Card'
}
</script>

<style>

</style>