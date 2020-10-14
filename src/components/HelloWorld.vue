<template>
  <h1>{{ msg }}</h1>
  <button
    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
    @click="() => count++"
  >
    count is: {{ count }}
  </button>
  <p>
    Edit <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script lang="ts">
export default {
  props: {
    msg: {
      type: String
    }
  },
  data() {
    return {
      count: 0 as number
    }
  }
}
</script>
