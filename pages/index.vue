<template>
  <div>
    <TopNav/>
    <bigImage image="https://img.freepik.com/darmowe-zdjecie/zolty-zonkil-narcyz-kwitnacy-w-ogrodzie_127675-2729.jpg?w=826&t=st=1679759619~exp=1679760219~hmac=16bc530ed103e815ea90b0515168ca251845e2dcf4822f3f3cba293d01b28582"/>
    <bigImage image="https://img.freepik.com/darmowe-psd/wiosna-kwiatowy-tlo-podium_23-2150154136.jpg?w=740&t=st=1679759809~exp=1679760409~hmac=397d6d3bda0afec08cd704055ac0eec8f2a8c5f758b1327d1a0b2b34b0e29d06"/>
  </div>
</template>

<script>
import TopNav from '../components/nav/TopNav.vue'
import bigImage from '../components/gallery/bigImage.vue'
export default {
  name: 'IndexPage',
  components: { TopNav, bigImage }
}
</script>
