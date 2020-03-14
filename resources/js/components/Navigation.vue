<template>
	<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
		<router-link :to="{name:'home'}" class="navbar-brand">LAVUE</router-link>
		<button class="navbar-toggler" type="button" data-togle="collapse" data-target="#navbarSupportContent" aria-controls="navbarSupportContent" aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
		</button>

		<div class="collapse navbar-collapse" id="navbarSupportContent">
			<ul class="navbar-nav mr-auto">
				<li class="nav-item active">
					<router-link :to="{ name: 'home'}" class="nav-link">Home</router-link>
				</li>
				<li class="nav-item">
					<router-link :to="{ name: 'about'}" class="nav-link">About</router-link>
				</li>
				<li class="nav-item">
					<router-link :to="{ name: 'contact'}" class="nav-link">Contact</router-link>
				</li>
			</ul>
			<form class="form-inline my-2 my-lg-0">
				<input type="search" class="form-control mr-sm-2" placeholder="Search" aria-label="Search">
				<button class="btn btn-outline-success my-2 my-sm-0" type="submit">Cari</button>
			</form>
		</div>
	</nav>
</template>

<script>
	export default {
		
	}
</script>