<script>
	import dashboard from '$lib/assets/dashboard.png';
	import user from '$lib/assets/user.png';
	import settings from '$lib/assets/settings.png';
</script>

<body>
	<nav>
		<div class="logo">LOGO</div>
		<p>Main Menu</p>
		<div class="menuSelection">
			<a class="select" href="/">
				<img src={dashboard} alt="" />
				Dashboard
			</a>
			<a class="select" href="/">
				<img src={user} alt="" />
				Users
			</a>
			<a class="select" href="/">
				<img src={dashboard} alt="" />
				Dashboard
			</a>
			<a class="select" href="/">
				<img src={user} alt="" />
				Users
			</a>
			<a class="select" href="/">
				<img src={dashboard} alt="" />
				Dashboard
			</a>
			<a class="select" href="/">
				<img src={settings} alt="" />
				Settings
			</a>
		</div>
	</nav>
</body>

<style lang="scss">
	@import url('https://fonts.googleapis.com/css2?family=AR+One+Sans:wght@500&family=Poppins&family=Roboto:wght@300&display=swap');

	* {
		margin: 0;
		color: white;
		font-family: 'Poppins';
		font-size: 20px;
	}
	body {
		nav {
			padding: 2% 0% 2% 2%;
			height: 100%;
			width: 13%;
			position: fixed;
			background-color: #2f363e;
			z-index: 1;
			overflow-x: hidden;
			.logo {
				margin-bottom: 30px;
			}
			p {
				margin-bottom: 30px;
				color: #626a6d;
			}
			.menuSelection {
				.select {
					display: flex;
					align-items: center;
					padding: 20px 0 20px 0;
					font-size: 17px;
					text-decoration: none;
					&:hover {
						background: linear-gradient(
							90deg,
							rgba(17, 180, 153, 0) 0%,
							rgba(17, 180, 153, 0.08) 63%,
							rgba(17, 180, 153, 0.15) 100%
						);
					}
					img {
						width: 36px;
						margin-right: 25px;
						filter: invert(100%);
					}
				}
			}
		}
	}
</style>
