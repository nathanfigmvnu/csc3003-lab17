<template>
  <v-card class="ma-2 photo">
    <v-img v-bind:src="photo_url" />
    <v-card-title>
      <div class="text-truncate">{{title}}</div>
    </v-card-title>
  </v-card>
</template>

<script>
  export default {
    props: {
      photo_url: String,
      title: String,
    }
  }
</script>

<style>
.photo {
  width: 300px;
}
</style>
