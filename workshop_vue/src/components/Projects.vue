<template>
	<div class="grid-container-projects">
		<CardProject></CardProject>
		<CardProject></CardProject>
		<CardProject></CardProject>
		<CardProject></CardProject>
		<CardProject></CardProject>
		<CardProject></CardProject>
	</div>
</template>

<script setup lang="ts">
import CardProject from "./CardProject.vue";
</script>

<style scoped>
.grid-container-projects {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	width: 100%;
	gap: 22px;
	padding-top: 30px;
}
</style>
