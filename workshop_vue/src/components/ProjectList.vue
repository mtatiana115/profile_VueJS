<template>
	<div class="project-list">
		<h3>Project List</h3>
		<table>
			<thead>
				<tr>
					<th>Project</th>
					<th>Leader</th>
					<th>Team</th>
					<th>Progress</th>
					<th>Action</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>BBC E-commerce App</td>
					<td>Eileen</td>
					<td>React Developers</td>
					<td>76%</td>
					<td>⋮</td>
				</tr>
				<tr>
					<td>Falcon Logo Design</td>
					<td>Owen</td>
					<td>UI Designers</td>
					<td>25%</td>
					<td>⋮</td>
				</tr>
				<tr>
					<td>Dashboard Design</td>
					<td>Keith</td>
					<td>VueJS Developers</td>
					<td>45%</td>
					<td>⋮</td>
				</tr>
			</tbody>
		</table>
	</div>
</template>

<script setup lang="ts"></script>

<style scoped>
.project-list {
	background-color: #fff;
	padding: 20px;
	border-radius: 8px;
	box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

table {
	width: 100%;
	border-collapse: collapse;
}

th,
td {
	padding: 10px;
	text-align: left;
}

th {
	background-color: #f0f0f0;
}

td {
	background-color: #fff;
	border-bottom: 1px solid #f0f0f0;
}
</style>
