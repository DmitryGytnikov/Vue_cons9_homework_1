<script>
import ClickCounter from "./components/ClickCounter.vue"
import HoverCounter from "./components/HoverCounter.vue"

export default {
	components: {
		ClickCounter,
		HoverCounter,
	},
}
</script>

<template>
	<click-counter />
	<!-- <hr /> -->
	<hover-counter />
</template>
