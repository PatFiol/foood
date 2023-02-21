<template>
  <footer :style="footerStyles">
    <p>&copy; 2020</p>
  </footer>
</template>

<script>
export default {
  data () {
    return {
      footerStyles: {
        backgroundColor: 'black',
        color: 'white',
        height: '200px',
        textAlign: 'center',
        padding: '5rem'
      }
    }
  }
}
</script>

<style>
@import '../assets/css/main.css';
</style>
