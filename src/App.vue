<template>
  <div>
    <button @click="increment">Click me!</button>
    <p>You've clicked the button {{ count }} times.</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
  },
};
</script>
