<template>
  <div class="profile">
    <div class="grid-y">
      <div class="cell small-12 medium-8 large-8  profile_details">
        <!--        <img src="./img/image-jeremy.png" alt="...">-->
        <img/>
        <p>Report for
          <br>
          <span>
          Jeremy
          <br>
          Robson
        </span>
        </p>
      </div>
      <div class="cell small-12 medium-4 large-4 profile_schedule">
        <p class="profile_schedule_first">Daily</p>
        <p class="profile_schedule_second">Weekly</p>
        <p class="profile_schedule_third">Monthly</p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "Profile",
  data() {
    return {
      // logo: require('../../public/images/image-jeremy.png'),
      // name : 'image-jeremy.png'
    }
  },
  methods: {
    loadImg: function (path) {
      require(path)
    }
  }
}
</script>

<style scoped>

</style>