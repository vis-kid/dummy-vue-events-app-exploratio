<template>
<div id="nav">
  <nav>
    <router-link to="/">Real World Events</router-link> |
    <router-link :to="{ name: 'event-list' }">List</router-link> |
    <router-link :to="{ name: 'event-create' }">Create an Event</router-link> |
  </nav>
</div>
</template>

<script>
  export default {
    	
  }
</script>

<style lang="sass" scoped>
  
</style>
