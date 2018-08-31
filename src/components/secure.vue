<template>
    <div id="secure">
        <h1>Secure Area</h1>
        <h1>{{ msg }}</h1>
        <p>
            This is a secure area man.
        </p>
    </div>
</template>

<script>
export default {
  name: 'Secure',
  data () {
    return {msg: 'Welcome to Your Secure App'}
  }
}
</script>

<style scoped>
#secure {
  background-color: #FFFFFF;
  border: 1px solid #CCCCCC;
  padding: 20px;
  margin-top: 10px;
}
</style>
