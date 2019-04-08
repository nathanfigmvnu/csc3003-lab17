<template>
  <v-app>
    <!-- Add a toolbar with a title at the top here -->
    <v-content>
      <v-container>
      <v-layout justify-center row wrap>
            <Photo title="Eggs and baked beans. Yum." photo_url="http://csc3003.com/lab4/0.jpg" />
            <!-- Once your Photo component is complete, add 15 more photos-->
      </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import Photo from './components/Photo'

export default {
  name: 'App',
  components: {
    Photo
  }
}
</script>
