<template>
	<div class="card">
		<div class="card-header">
			<div class="avatar">
				<img src="/profilepic.jpg" alt="Avatar" />
			</div>
			<div class="user-info">
				<h3>{{ name }}</h3>
				<span>{{ role }}</span>
			</div>
		</div>
		<div class="skills">
			<span v-for="skill in skills" :key="skill" class="skill">{{
				skill
			}}</span>
		</div>
		<div class="card-content">
			<div class="stats">
				<div>
					<strong>{{ projects }}</strong>
					<span>Projects</span>
				</div>
				<div>
					<strong>{{ tasks }}</strong>
					<span>Tasks</span>
				</div>
				<div>
					<strong>{{ connections }}</strong>
					<span>Connections</span>
				</div>
			</div>
			<div class="actions">
				<button class="connect-button">Connect</button>
				<button class="message-button">
					<i class="bx bx-envelope"></i>
				</button>
			</div>
		</div>
	</div>
</template>

<script setup lang="ts">
const name = "Mark Gilbert";
const role = "UI Designer";
const skills = ["Figma", "Sketch"];
const projects = 18;
const tasks = 834;
const connections = 129;
</script>

<style scoped>
.card {
	background-color: #fff;
	border-radius: 8px;
	box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
	padding: 15px;
	display: flex;
	flex-direction: column;
	width: 300px;
	text-align: center;
	img {
		width: 80px;
		height: 80px;
		border-radius: 50%;
		margin-bottom: 10px;
	}
}

.card-header {
	display: flex;
	flex-direction: column;
	align-items: center;
	margin-bottom: 10px;
}

.avatar img {
	width: 80px;
	height: 80px;
	border-radius: 50%;
	margin-bottom: 10px;
}

.user-info h3 {
	font-size: 18px;
	margin: 0;
}

.user-info span {
	color: #888;
	font-size: 14px;
}

.skills {
	display: flex;
	justify-content: center;
	gap: 10px;
	margin-bottom: 10px;
}

.skill {
	background-color: #f0f0f0;
	border-radius: 12px;
	padding: 5px 10px;
	font-size: 12px;
}

.card-content {
	display: flex;
	flex-direction: column;
	align-items: center;
}

.stats {
	display: flex;
	justify-content: space-between;
	width: 100%;
	margin-bottom: 15px;
}

.stats div {
	text-align: center;
}

.stats strong {
	display: block;
	font-size: 16px;
}

.stats span {
	color: #888;
	font-size: 12px;
}

.actions {
	display: flex;
	gap: 10px;
}

.connect-button,
.message-button {
	background-color: #6200ea;
	color: white;
	padding: 8px 12px;
	border-radius: 8px;
	border: none;
	cursor: pointer;
}

.connect-button {
	background-color: #6200ea;
}

.message-button {
	background-color: #f0f0f0;
	color: #222;
}
</style>
