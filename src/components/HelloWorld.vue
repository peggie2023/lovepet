<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Want to go out for a nice hangout and don't want to leave your fur baby<br>
      alone at home?<br>
      Want to go to a couple of days trip but don't know who can take care of<br>
      them while you are away?<br>
      Check out us to have a worry-free vacation!
    </p>
    <h3>Who are we?</h3>
    <ul>
      <p>
        Professional pet care taker. We are a couple who have experience take care of our furry friends for three years. We work<br>
        from home everyday so can provide enough attention and playtime to your pets. 
      </p>
    </ul>
    <h3>What we do?</h3>
    <ul>
    </ul>
    <h3>Our rates</h3>
    <ul>
    </ul>
    <h3>Our happy customers</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
