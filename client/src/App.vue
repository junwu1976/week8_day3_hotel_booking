<template>
  
</template>

<script>
export default {
  mounted(){
    fetch('http://localhost:3000/api/bookings')
    .then( res => res.json() )
    .then( data => console.log(data))
  }
}
</script>

<style>

</style>