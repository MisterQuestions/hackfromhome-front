<template>
  <div>
    <div class="container">
      <div class="message">
        Learn and practice
        <br />how to code
        <button class="get-started">Get started</button>
      </div>
      <img
        src="https://images.unsplash.com/photo-1513530534585-c7b1394c6d51?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1351&q=80"
        alt="coding photo"
      />
    </div>
    <div class="orange"></div>
  </div>
</template>

<style scoped>
.container {
  margin: 0 auto;
  margin-top: 5em;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 3fr;
}

.message {
  display: flex;
  flex-direction: column;
  font-size: 5em;
  grid-column: 1 / 2;
  grid-row: 1 / 2;
  margin: 0.3em;
}

img {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
  overflow: hidden;
  height: 100%;
  margin: 0.3em;
}

.get-started {
  margin: 1em 2em 2em 0;
  padding: 0.5em 2em;
  align-self: flex-start;
  font-size: 25px;
  border-radius: 30px;
  background: black;
  color: white;
}

.orange {
  position: absolute;
  width: 30%;
  height: 100%;
  left: 70%;
  top: 0;
  background-color: #f29b19;
  z-index: -3;
  border-radius: 100px 0 0 100px;
}
</style>
