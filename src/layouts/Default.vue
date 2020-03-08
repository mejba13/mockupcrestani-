<template>
  <div>
<!--    <header class="header">-->
<!--      <strong>-->
<!--        <g-link to="/">{{ $static.metadata.siteName }}</g-link>-->
<!--      </strong>-->
<!--      <nav class="nav">-->
<!--        <g-link class="nav__link" to="/">Home</g-link>-->
<!--        <g-link class="nav__link" to="/about/">About</g-link>-->
<!--      </nav>-->
<!--    </header>-->
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