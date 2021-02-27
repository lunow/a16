<template>
  <div>
    <h1>A16</h1>
    <input type="password" placeholder="Bitte Passwort eingeben" autofocus>

  </div>
</template>

<script>
export default {}
</script>


<style>
  html, body, body>div {
    padding: 0;
    margin: 0;
    width: 100vw;
    height: 100vh;
  }
  body {
    background-image:url('/a16-bg.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
  }
  body div {
    overflow:hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  h1 {
    /* color: #fff; */
    text-transform: uppercase;
    font-size: 20vw;
    font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: bold;
    opacity: 1;
    color: rgb(31, 37, 13);
  }
  input {
    position: absolute;
    outline: none;
    font-size: 3vw;
    font-family: monospace;
    padding: 5px;
    left: 0;
    bottom: 0;
    width: 100%;
    background: rgba(255,255,255,0.7);
  }
  ::placeholder {
    color: black;
    text-align: center;
    font-size: 3vw;
    opacity: 1;
  }
</style>
