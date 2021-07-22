<template>
  <div id="app">
    {{msg}} 

  </div>

</template>

<script>


export default {
  name: 'App',
  components: {
    
  },
  data() {
    return {
      todos : [
        {
          id: 1,
          title: 'Todo One',
          completed: false
        },
        {
          id: 2,
          title: 'Todo two',
          completed: true
        },
        {
          id: 3,
          title: 'Todo three',
          completed: false
        }
      ]
    }
  }
}
</script>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, Helvetica, Sans-Serif;
    line-height: 1.4;
}

</style>
