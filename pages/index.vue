<template>
  <div>
    <div>{{ count }}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 100,
    }
  },
  methods: {
    plus() {
      this.count += 1
    },
    minus() {
      this.count -= 1
    },
  },
}
</script>
