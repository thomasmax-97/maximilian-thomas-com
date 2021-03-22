<template>
  <div>
    <carousel-3d
      :width="1190"
      :border="1"
      :height="1684">
      <slide :index="0">
        <img
          :src="require(`~/assets/images/resume1.jpg`)"
          class="resume-img">
      </slide>
      <slide :index="1">
        <img :src="require(`~/assets/images/resume2.jpg`)" >
      </slide>
      <slide :index="2">
        <img
          :src="require(`~/assets/images/resume3.jpg`)">
      </slide>
    </carousel-3d>
  </div>
</template>
