<template>
  <div class="file-input">
    <form method="POST">
      <input type="file" :name="name" id="file-input" v-show="false">
    </form>
  </div>
</template>

<script>
export default {
  name: 'file-input',
  data() {
    return {
      name: 'custom-upload'
    }
  }
}
</script>

<style>

</style>