<template>
  <form>
    <div>
      <label>Title</label>
      <input type="text" />
    </div>

    <div>
      <label>Description</label>
      <input type="text" />
    </div>
    <div>
      <button>Add Book</button>
    </div>
  </form>
</template>

<script>
export default {
  emits: [],
  data() {
    return {};
  },
  methods: {},
};
</script>

<style scoped>
form {
  margin: 2rem auto;
  max-width: 40rem;
  padding: 1rem;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
}

form div {
  margin: 1rem 0;
}

input {
  padding: 0.15rem;
}
label {
  font-weight: bold;
  margin-right: 1rem;
  width: 7rem;
  display: inline-block;
}
</style>