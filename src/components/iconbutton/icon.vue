<template>
	<svg class="icon" aria-hidden="true">
		<use :xlink:href="'#icon-'+name"></use>
	</svg>
</template>

<script>
    export default {
        props: ['name']
    }
</script>

<style>
</style>