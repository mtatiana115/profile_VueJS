<template>
	<div class="grid-container-connections">
		<CardConnections></CardConnections>
		<CardConnections></CardConnections>
		<CardConnections></CardConnections>
		<CardConnections></CardConnections>
		<CardConnections></CardConnections>
		<CardConnections></CardConnections>
	</div>
</template>

<script setup lang="ts">
import CardConnections from "./CardConnections.vue";
</script>

<style scoped>
.grid-container-connections {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	width: 100%;
	gap: 22px;
	padding-top: 30px;
}
</style>
