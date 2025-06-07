<script>
import counter from "@/mixins/counter"

export default {
	mixins: [counter],
}

// export default {
// 	data() {
// 		return { count: 0 }
// 	},
// 	methods: {
// 		increment() {
// 			this.count++
// 		},
// 	},
// }
</script>

<template>
	<div @mouseover="increment">Hovers: {{ count }}</div>
</template>

<style scoped>
div {
	background: #513a9b;
}
</style>
