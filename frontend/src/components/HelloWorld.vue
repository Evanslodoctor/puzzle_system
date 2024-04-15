<template>
  <div class="welcome-page">
    <h1>Welcome to the Online Examination Site</h1>
    <p>Click <a href="http://127.0.0.1:8000/">here</a> to continue.</p>
  </div>
</template>

<script>
export default {
  name: "WelcomePage",
};
</script>

<style scoped>
body {
  background-color: orange; /* Set background color of the entire page to orange */
}

.welcome-page {
  text-align: center;
  margin-top: 50px;
}

h1 {
  font-size: 24px;
  margin-bottom: 20px;
}

p {
  font-size: 16px;
  line-height: 1.5;
}

a {
  color: #42b983;
  text-decoration: none;
}
</style>
