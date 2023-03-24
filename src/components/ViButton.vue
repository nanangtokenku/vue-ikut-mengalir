<template>
  <button @click="showAlert">Say Hello</button>
</template>

<script>
export default {
  name: 'ViButtonName',
  props: {
    judul: String,
  },
  methods: {
    showAlert() {
      alert('Hi');
    },
  },
};
</script>
