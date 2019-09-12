<template>
  <div id="app">
    <div class="w-400">
      <file-input />
      <file-upload />
    </div>
  </div>
</template>

<script>
import FileUpload from "./components/FileUpload";
import FileInput from "./components/FileInput";

export default {
  name: "app",
  components: { FileUpload, FileInput }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html,
body {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.w-400 {
  width: 700px;
  margin: 0 auto;
}
</style>
