<template>
	<p class="message">message: {{ msg }}</p>
</template>

<script>
export default {
	data () {
		return { msg: 'hello, there!' }
	}
}
</script>

<style>
.message { color: #42b983; }
</style>
