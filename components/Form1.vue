<template>
  <div>
    <v-parallax
      class="a"
      src="https://images.pexels.com/photos/1342460/pexels-photo-1342460.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
    >
      <div class="abc text-center">
        <h3 class="ab text-uppercase">all access</h3>
        <h4 class="xy">Access to ALL videos</h4>
      </div>
    </v-parallax>
  </div>
</template>


<script>
export default {
  // data: () => ({
  //   links: ['Dashboard', 'Messages', 'Profile', 'Updates'],
  // }),
}
</script>
<style >
body {
  /* background-image: url('https://images.pexels.com/photos/1342460/pexels-photo-1342460.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940'); */
  background-size: cover;
  font-family: 'Roboto Slab', serif;
}
/* .a {
  border: 1px solid black;
} */
.ab {
  font-size: 70px;
  text-shadow: 0 0 3px #ff0000, 0 0 5px yellow;
}
.xy {
  font-size: 30px;
  text-shadow: 0 0 3px #ff0000, 0 0 5px yellow;
  background: #000;
  opacity: 0.8;
}
</style>