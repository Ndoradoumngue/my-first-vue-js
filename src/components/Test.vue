<template>
<div class="test">

{{msg}} {{user.first_name}} {{user.last_name}}

</div>
</template>

<script>

export default {
	name: 'test',
	data() {
		return {
			msg: 'Hello, ',

			user: {
				first_name: 'Christian',
				last_name: 'Ndoradoumngue'
			}
			
		}
	}
}


</script>

<style scoped>

</style>
