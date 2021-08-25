<template>
  <nuxt-link :to="'jokes/'+ id">
      <div class="joke">
          <p>{{joke}}</p>
      </div>
  </nuxt-link>
</template>

<script>
export default {
    name: 'Joke',
    props: ['joke','id']
}
</script>

<style>
.joke{
    padding: 10px;
    border: 1px dotted grey;
    margin: 1rem 0;
}
</style>