<template>
<div>
  <h1>Event List</h1>
  <EventCard/>
</div>
</template>

<script>
import EventCard from '@/components/EventCard.vue';

export default {
  components: {
    EventCard:EventCard
  }
    
}
</script>
