<template>
  <div id="app">
    <Editor />
  </div>
</template>

<script>
import Editor from "./components/Editor";

export default {
  name: "App",
  components: {
    Editor,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
}

* {
  box-sizing: border-box;
}

input {
  width: 400px;
  padding: 8px 12px;
  font-family: sans-serif;
}
</style>
