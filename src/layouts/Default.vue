<template>
  <div>
    <div class="layout">
        <slot/>
    </div>
  	<FOOTER/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import FOOTER from '~/components/Footer.vue'

export default {
	components: {
		FOOTER
	}
}
</script>