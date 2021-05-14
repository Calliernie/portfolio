<template>
  <div class="mainDiv">
    <v-btn raised class="primary" @click="onPickFile">Upload Image</v-btn>
    <input type="file" style="display: none" ref="fileInput" accept="image/*" />
  </div>
</template>

<script>
export default {
    name: "Test",
  data() {
    return {};
  },
  methods: {
    onPickFile() {
      this.$refs.fileInput.click();
    },
  },
};
</script>
