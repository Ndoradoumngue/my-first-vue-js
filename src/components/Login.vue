<template>

<div class="login">



<input type="text" v-model="title">
<br/>

{{title}}

<button v-on:click="sayHi()">Say hi, na!</button>

</div>


</template>


<script>

export default {
	name: 'login',

	data() {
		return {
			title: 'Login Portal',
		}
	},

	methods: {
		sayHi: function() {
			alert('hi, man')
		}
	}
}

</script>



