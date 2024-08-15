<template>
	<div class="card">
		<div class="card-header">
			<div class="title">
				<div class="icon"><img src="/profilepic.jpg" alt="Icon" /></div>
				<h3>Social Banners</h3>
			</div>
			<div class="client">Client: Christian Jimenez</div>
			<div class="menu">⋮</div>
		</div>
		<div class="card-content">
			<div class="budget">$24.8k / $18.2k</div>
			<div class="label">Total Budget</div>
			<p>
				We are Consulting, Software Development and Web Development Services.
			</p>
			<div class="details">
				<div class="hours">All Hours: 380/244</div>
				<div class="task">Task: 290/344</div>
				<div class="progress-bar">
					<div class="progress" style="width: 95%"></div>
				</div>
				<div class="status">
					<span class="days-left">28 Days left</span>
					<span class="completion">95% Completed</span>
				</div>
			</div>
		</div>
		<div class="card-footer">
			<div class="avatars">
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
			</div>
			<div class="members">280 members</div>
			<div class="comments">15</div>
		</div>
	</div>
</template>
<script setup lang="ts"></script>

<style scoped>
.card {
	background-color: #fff;
	border-radius: 8px;
	box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
	padding: 13px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	width: 31%;
	img {
		width: 40px;
		height: 40px;
	}
}

.card-header {
	display: flex;
	justify-content: space-between;
	align-items: center;
	margin-bottom: 10px;
}

.title {
	display: flex;
	align-items: center;
}

.title h3 {
	margin-left: 10px;
	font-size: 18px;
}

.client {
	font-size: 14px;
	color: #888;
	margin-left: 10px;
}

.menu {
	font-size: 20px;
	cursor: pointer;
}

.card-content {
	font-size: 14px;
	color: #666;
	margin-bottom: 10px;
}

.budget {
	font-size: 16px;
	font-weight: bold;
}

.label {
	color: #888;
	font-size: 12px;
	margin-bottom: 10px;
}

.details {
	margin-top: 10px;
}

.hours,
.task {
	font-size: 14px;
	margin-bottom: 5px;
}

.progress-bar {
	background-color: #e0e0e0;
	border-radius: 8px;
	overflow: hidden;
	height: 8px;
	margin: 10px 0;
}

.progress {
	background-color: #6200ea;
	height: 100%;
}

.status {
	display: flex;
	justify-content: space-between;
	font-size: 12px;
	color: #888;
}

.days-left {
	background-color: #e0f7fa;
	padding: 5px 10px;
	border-radius: 12px;
}

.card-footer {
	display: flex;
	align-items: center;
	justify-content: space-between;
	margin-top: 10px;
}

.avatars {
	display: flex;
}

.avatar {
	width: 30px;
	height: 30px;
	border-radius: 50%;
	margin-right: -10px;
	border: 2px solid #fff;
}

.members,
.comments {
	font-size: 12px;
	color: #888;
}
</style>
