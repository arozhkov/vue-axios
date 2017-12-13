<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <users-list></users-list>
    <trips-list></trips-list>
  </div>
</template>

<script>
import UsersList from '@/components/UsersList'
import TripsList from '@/components/TripsList'

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    UsersList,
    TripsList
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
