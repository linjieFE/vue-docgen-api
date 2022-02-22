<template>
	<div>
		<Input />
		<slot />
	</div>
</template>
<script>
import Input from '../Input/Input.vue'

/**
 * @displayName FilterWithSlot
 */
export default {
	components: { Input },
}
</script>
