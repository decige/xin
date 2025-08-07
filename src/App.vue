<template>
 <ti></ti>
 <shuo></shuo>
 <hr></hr>
 <xianshi></xianshi>
 <SpeedInsights />
  </template>
  <script>
  import ti from './components/title.vue'
  import shuo from './components/shuo.vue'
  import xianshi from './components/xianshi.vue'
  import { SpeedInsights } from "@vercel/speed-insights/next"
  const s={
components:{//要引用组件在这声明
  ti,
  shuo,
  xianshi,
}
  }

 export default s
</script>
  <style></style>