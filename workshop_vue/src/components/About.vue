<template>
	<div class="about-card">
		<h3>About</h3>
		<ul>
			<li>Name: John Doe</li>
			<li>Status: Active</li>
			<li>Role: Developer</li>
			<li>Country: COL</li>
			<li>Language: English</li>
		</ul>
		<div class="contacts">
			<div>Contact: +123 456 7890</div>
			<div>Skype: john.doe</div>
			<div>Email: johndoe@example.com</div>
		</div>
		<div class="teams">
			<div>Backend Developer (26 Members)</div>
			<div>VueJS Developer (18 Members)</div>
		</div>
	</div>
</template>

<script setup lang="ts"></script>

<style scoped>
.about-card {
	background-color: #fff;
	padding: 20px;
	border-radius: 8px;
	box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
	gap: 10px;
}
</style>
