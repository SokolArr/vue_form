<template>
  <div id="app">
    <Form />
  </div>
</template>

<script>
import Form from "./components/Form.vue";

export default {
  name: "App",
  components: {
    Form
  }
};
</script>

<style>
#app {
  font-family: "Roboto", sans-serif;
  color: #2a2a2a;
  padding: 24px;
  box-sizing: border-box;
}

html,
body {
  font-size: 18px;
}

#app {
  height: 100%;
  align-items: center;
}

* {
  box-sizing: border-box;
}
</style>
