<template>
  <div>
    <h5>Hello this is my components</h5>
    <div>
      <p>My name is {{ name }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      default: 'Mark'
    }
  }
}
</script>
