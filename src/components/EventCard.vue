<template>
<router-link :to="{ name: 'event-show', params: { id: '1' } }">
  <div>
    <span>@{{ event.time }} on {{ event.date }}</span>
    <h4>{{ event.title }}</h4>
    <BaseIcon name="users">{{ event.attendees.length }} attending</BaseIcon>
  </div> 
</router-link>
</template>

<script>
  export default {
    props: {
      event: Object
    }  
  }
</script>

<style lang="sass" scoped>
h4
  color: green
</style>
