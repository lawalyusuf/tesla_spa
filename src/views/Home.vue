<template>
  <div>
    <promo></promo>
    <specifications></specifications>
    <interior></interior>
    <core-features></core-features>
    <order-now></order-now>
  </div>
</template>

<script>
import Promo from '../components/Promo.vue'
import Specifications from '../components/Specifications.vue'
import Interior from '../components/Interior.vue'
import CoreFeatures from '../components/CoreFeatures.vue'
import OrderNow from '../components/OrderNow.vue'
export default {
  components: { Promo, Specifications, Interior, CoreFeatures, OrderNow },

}
</script>

<style>

</style>