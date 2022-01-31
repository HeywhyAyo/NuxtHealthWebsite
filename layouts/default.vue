<template>
 <div>
     <navigation/>
 <Nuxt />
    <s-footer />
 </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue'
import SFooter from '~/components/SFooter.vue'
export default {
  components: { Navigation, SFooter },

}
</script>
