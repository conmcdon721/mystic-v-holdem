<template>
  <header>
    <h1>Hello! Please enter your name below.</h1>
    <p>Your name is {{ username }}</p>
    <input v-model="username" placeholder="Your name here">
    <!-- <input type="submit"> -->
  </header>
</template>

<script>
export default {
  name: "SeatUsher",
  data() {
    return {
      username:''
    }
  }
};
</script>