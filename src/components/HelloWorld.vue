<template>
  <div>
    <ion-toolbar>
      <ion-segment>
        <ion-segment-button value="all" checked>All</ion-segment-button>
        <ion-segment-button value="favorites">Favorites</ion-segment-button>
      </ion-segment>
    </ion-toolbar>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
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
