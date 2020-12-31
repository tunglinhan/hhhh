<template lang="pug">
.whole
  .h-icon
  .t1
    p 關於學院
  .t2
    p 學院師資
  .t3
    p 學院規章
  .t4
    p 招生訊息
  .t5
    p 榮譽榜
  .logo
  .t6
    p 活動花絮
  .t7
    p 藝院影音
  .t8
    p 藝術學報
  .t9
    p 聯絡資訊
  .m-icon
  .photo
  .slide
    .p1
    .p2
    .p3
    .p4
    .p5
    .p6
    .p7
    .p8
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass">
.whole
  position: relative
  width: 1440px
  height: 1024px
  background: #FFFFFF
.h-icon
  background-image: url("../assets/home.png")
  position: absolute
  width: 40px
  height: 40px
  left: 36px
  background-size: cover
.t1
  position: absolute
  width: 109px
  height: 40px
  left: 153px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t1:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t2
  position: absolute
  width: 109px
  height: 40px
  left: 302px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t2:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t3
  position: absolute
  width: 109px
  height: 40px
  left: 451px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t3:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t4
  position: absolute
  width: 109px
  height: 40px
  left: 600px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t4:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t5
  position: absolute
  width: 109px
  height: 40px
  left: 749px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t5:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.logo
  background-image: url("../assets/nthuart.png")
  position: absolute
  width: 650px
  height: 650px
  left: 8px
  top: -30px
  background-size: cover
.t6
  position: absolute
  width: 109px
  height: 40px
  left: 136px
  top: 550px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t6:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t7
  position: absolute
  width: 109px
  height: 40px
  left: 285px
  top: 550px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t7:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t8
  position: absolute
  width: 109px
  height: 40px
  left: 434px
  top: 550px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t8:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.t9
  position: absolute
  width: 109px
  height: 40px
  left: 583px
  top: 550px
  font-family: Yesteryear
  font-style: normal
  font-weight: normal
  font-size: 12px
  line-height: 15px
  text-transform: uppercase
  color: #000000
  text-align:center
  border-radius: 20px
  background: #ffffff
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
  cursor: pointer
  transition: all 0.2s ease-out
.t9:hover
  border-radius: 20px
  background: linear-gradient(145deg, #e6e6e6, #ffffff)
  box-shadow:  20px 20px 60px #d9d9d9, -20px -20px 60px #ffffff
.m-icon
  background-image: url("../assets/max.png")
  position: absolute
  width: 40px
  height: 40px
  left: 36px
  top: 550px
  background-size: cover
.photo
  background-image: url("../assets/circle.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p1
  background-image: url("../assets/w-1.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p2
  background-image: url("../assets/w-2.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p3
  background-image: url("../assets/w-3.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p4
  background-image: url("../assets/w-4.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p5
  background-image: url("../assets/w-5.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p6
  background-image: url("../assets/w-6.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p7
  background-image: url("../assets/w-7.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
.p8
  background-image: url("../assets/w-8.png")
  position: absolute
  width: 1280px
  height: 720px
  top: -90px
  background-size: cover
</style>