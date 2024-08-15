<template>
	<div class="card">
		<div class="card-header">
			<img src="/profilepic.jpg" alt="React Logo" class="logo" />
			<div class="title">React Developers</div>
			<div class="favorite">★</div>
			<div class="menu">⋮</div>
		</div>
		<div class="card-content">
			<p>
				We don't make assumptions about the rest of your technology stack, so
				you can develop new features in React.
			</p>
		</div>
		<div class="card-footer">
			<div class="avatars">
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
				<img src="/profilepic.jpg" alt="Avatar" class="avatar" />
			</div>
			<div class="tags">
				<span class="tag react">React</span>
				<span class="tag mui">MUI</span>
			</div>
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
}

.card-header {
	display: flex;
	align-items: center;
	justify-content: space-between;
	margin-bottom: 10px;
}

.logo {
	width: 40px;
	height: 40px;
}

.title {
	font-size: 18px;
	font-weight: bold;
	margin-left: 10px;
	flex-grow: 1;
}

.favorite,
.menu {
	font-size: 20px;
	cursor: pointer;
}

.card-content {
	font-size: 14px;
	color: #666;
	margin-bottom: 10px;
}

.card-footer {
	display: flex;
	align-items: center;
	justify-content: space-between;
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

.tags {
	display: flex;
}

.tag {
	background-color: #ececec;
	border-radius: 12px;
	padding: 5px 10px;
	font-size: 12px;
	margin-left: 5px;
	color: #555;
}

.react {
	background-color: #61dafb;
	color: #fff;
}

.mui {
	background-color: #007fff;
	color: #fff;
}
</style>
