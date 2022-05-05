<template>
  <button type="button" @click="count++">clicked {{ count }} time(s)</button>
</template>

<script>
export default {
  name: "DummyButton",

  data() {
    return {
      count: 0,
    };
  },
};
</script>

