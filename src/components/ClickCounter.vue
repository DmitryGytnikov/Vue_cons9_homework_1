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
	<button @click="increment">Clicks: {{ count }}</button>
</template>
