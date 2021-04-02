<template>
<div id="app">
  <div class="header">
    <router-link to="/">
      <div class="logo">
        <img src="/Swords.png">
      </div>
    </router-link>
    <div class="title">
      <h1>Nichols Family File Share!</h1>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <div id="space">
      <div><router-link to="/">Home</router-link></div>
      <div><router-link to="/upload">Manage</router-link></div>
    </div>
    <a href="https://github.com/Snicker7/file-sharing">Github</a>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: black;
  color: white;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 0px 5px 100px;
  background-color: #002E5D;
  color: white;
  width: 100%;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 50px;
  padding: 10px 100px 10px 70px;
  background: #e3e3e3;
  font-size: 12px;
  position: absolute;
  width: 100%;
  height: 40px;
}

.footer a {
  color: #000;
}

.space {
  display: flex;
  align-content: space-between;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}

img {
  width: 80px;
  padding-right: 10px;
}
</style>
