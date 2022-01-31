<template>
<div>

  <s-header />
  <s-content />
  <s-cta />
  <s-testimony />
</div>
</template>

<script>
import SContent from '~/components/SContent.vue'
import SCta from '~/components/SCta.vue'
import STestimony from '~/components/STestimony.vue'
import SHeader from '~/components/SHeader.vue'
export default {
  components: { SHeader, SContent, SCta, STestimony },

}
</script>
