<template>
  <div>
    <h1>Chuck Norris Jokes</h1>
    <ul>
      <li v-for="(joke, index) in chuck" :key="index">{{ joke.value }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      chuck: [
        {
          value: "Chuck Norris can skydive into outer space."
        },
        {
          value: "The chief export of Chuck Norris is pain."
        },
        {
          value: "Chuck Norris doesn't read books. He stares them down until he gets the information he wants."
        },
        {
          value: "Time waits for no man. Unless that man is Chuck Norris."
        },
        {
          value: "If you spell Chuck Norris in Scrabble, you win. Forever."
        },
      ]
    };
  }
};
</script>

<style scoped>
h1 {
  color: #333;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin-bottom: 10px;
  background-color: #f4f4f4;
  padding: 10px;
  border-radius: 5px;
}
</style>
