<template>
  <header>
    <h1>Hello! Please enter your name</h1>
    <form>
      <input placeholder="Your first name" />
      <input type="submit" @click="updateName" />
    </form>
    <p>Your name is currently registered as: {{ name }}</p>
  </header>
</template>

<script>
export default {
  name: "SeatUsher",

  data() {
    return {
      name: "(No name entered)",
    };
  },

  methods: {
    updateName() {
      console.log(document.fname);
      this.name = document.fname;
    },
  },
};
</script>