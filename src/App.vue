<template>
  <v-app>
    <v-toolbar class="blue-grey lighten-1">
      <v-toolbar-title class="headline white--text">Brunch Blog 2.0</v-toolbar-title>
    </v-toolbar>

    <v-content>
      <v-container>
      <v-layout justify-center row wrap>
            <Photo title="Eggs and baked beans. Yum." photo_url="http://csc3003.com/lab4/0.jpg" />
            <Photo title="A wholesome breakfast of raspberries." photo_url="http://csc3003.com/lab4/1.jpg" />
            <Photo title="Pancakes. Finally some good food." photo_url="http://csc3003.com/lab4/2.jpg" />
            <Photo title="Yogurt and some strawbs." photo_url="http://csc3003.com/lab4/3.jpg" />
            <Photo title="My coffee is staring back at me." photo_url="http://csc3003.com/lab4/4.jpg" />
            <Photo title="So healthy I can't keep it in the bowl." photo_url="http://csc3003.com/lab4/5.jpg" />
            <Photo title="Might delete this later idk" photo_url="http://csc3003.com/lab4/6.jpg" />
            <Photo title="Anyone actually own these honey things" photo_url="http://csc3003.com/lab4/7.jpg" />
            <Photo title="This is my PS4 wallpaper don't @ me" photo_url="http://csc3003.com/lab4/8.jpg" />
            <Photo title="Haha so cute. Imma eat them." photo_url="http://csc3003.com/lab4/9.jpg" />
            <Photo title="There is nothing edible in this photo." photo_url="http://csc3003.com/lab4/10.jpg" />
            <Photo title="Donuts in a white room." photo_url="http://csc3003.com/lab4/11.jpg" />
            <Photo title="The English take pride in this." photo_url="http://csc3003.com/lab4/12.jpg" />
            <Photo title="It's just a bagel okay." photo_url="http://csc3003.com/lab4/13.jpg" />
            <Photo title="Okay who did this." photo_url="http://csc3003.com/lab4/14.jpg" />
            <Photo title="Honestly this is the best thing here." photo_url="http://csc3003.com/lab4/15.jpg" />
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
