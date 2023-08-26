<template>
  <div class="container">
    <form>
      <p class="fsize">Login</p>
      <input type="text" placeholder="email address" />
      <input type="password" placeholder="Password" />
      <button type="submit">ログイン</button>
    </form>
  </div>
</template>

<style scoped>
.fsize {
  font-size: 24px;
  text-align: center;
}

.container {
  max-width: 400px;
  margin: 150px auto;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
}

input[type="text"],
input[type="password"] {
  width: 93%;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button[type="submit"] {
  width: 100%;
  padding: 10px;
  background-color: #4caf50;
  color: #ffffff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button[type="submit"]:hover {
  background-color: #45a049;
}
</style>
