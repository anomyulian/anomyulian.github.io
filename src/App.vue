<template>
	<div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <!-- <router-view/> -->
    <div class="card-root">
    	<div class="card-wrapper">
    		<div class="card-menu">
    			<router-link to="/" class="card-menu-item">Home</router-link>
    			<router-link to="/contact" class="card-menu-item">Contact</router-link>
    			<router-link to="/work" class="card-menu-item">Work</router-link>
    			<router-link to="/about" class="card-menu-item">About Me</router-link>
    			<router-link to="/other" class="card-menu-item">Other Info</router-link>
    		</div>
    		<div class="card-content">
    			<router-view/>
    		</div>
    	</div>
    </div>
  </div>
</template>

<style lang="scss" scoped="">

	.card {
		&-root {
			background-color: #f8f8f8;
			height: 560px;
			width: 1100px;
			margin: auto;
		}
		&-wrapper {
			display: flex;
			padding-top: 120px;
		}
		&-menu {
			width: 240px;
			padding: 6px 0 6px 64px;
			font-size: 12px;
			font-weight: bold;
		}
		&-menu-item {
			display: block;
			padding: 8px 0;
			text-decoration: none;
			text-transform: uppercase;
			color: #464646;
		}
		&-content {
	    padding: 0 40px;
	    width: 100%;
		}
	}


  // root
  .card-3 {
  	box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
  }
</style>


<style lang="scss">
// #1C2252
// #1C2252 tier 1

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700;900&display=swap');
body {
	margin: 0;
}
p {
	line-height: 1.6;
}

#app {
	font-family: Roboto, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	background-color: #622D84;
	height: calc(100vh - 100px);
	color: #464646;
	padding-top: 100px;
	font-size: 14px;
}

#nav {
	padding: 30px;

	a {
		font-weight: bold;
		color: #2c3e50;

		&.router-link-exact-active {
			color: #42b983;
		}
	}
}
</style>
