<template>
  <div>
		<ul class="nav">
			<li class="aa"><router-link to='/home'>首页</router-link></li>
			<li><router-link to='/news'>新闻</router-link></li>
		</ul>
		<router-view></router-view>
  </div>
</template>

<script>

</script>

<style lang="scss">
.nav {
	width: 100%;
	overflow: hidden;

	li {
		width: 100px;
		text-align: center;
		float: left;

		a {
			width: 100%;
			display: inline-block;
			color: #42b983;
		}

		.router-link-active {
			color: #f60;
			border-bottom: 2px solid #f60;
		}
	}
}
</style>
