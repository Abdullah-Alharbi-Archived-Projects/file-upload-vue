<template>
  <div class="file-upload">
    <label for="file-input">
      <div class="box">
        <!-- TODO: add icon -->
        <div>
          <h1>Upload File</h1>
        </div>
        <div>
          <h4>Drag and drop or click here</h4>
        </div>
      </div>
    </label>
  </div>
</template>

<script>
export default {
  name: "file-upload"
};
</script>

<style scoped>
.file-upload {
  margin: 25px;
}

.box {
  display: flex;
  width: 100%;
  background-color: #1abc9c;
  border: 5px dashed lightgreen;
  flex-direction: column;
  border-radius: 10px;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  padding: 10px;
  height: 150px;
}

.box > * {
  color: #ffffff;
}
</style>