<template>
  <div>
    <!-- <Tutorial /> -->
    <input type="text" />
    <button @click="onClick">押したら乱数が出る</button>
  </div>
</template>

<script>
export default {
  methods: {
    onClick() {
      alert(Math.random())
    }
  }
}
</script>
