<script>
	import logo from '../../public/static/assets/personal-logo.svg'
</script>

<!DOCTYPE html>
<html lang="en">
	<head>
		<!-- Required meta tags -->
		<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />

		<!-- Bootstrap CSS -->
		<link
			rel="stylesheet"
			href="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css"
			integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO"
			crossorigin="anonymous"
		/>
	</head>

	<header class="nav-main"> 
		<nav class="navbar navbar-light shift container">
			<a class="navbar-brand" href="/" id="logo">
				<!-- container d-flex justify-content-between -->
				<img src={logo} width="45" height="45" class="d-inline-block align-top personal-logo" alt="personal-logo">
			</a>
			<ul class="hvr-nav">
				<li><a href="/about">About</a></li>
				<!-- <li><a href="/design">Design</a></li>
				<li><a href="/coding">Coding</a></li> -->
				<li><a href="https://www.linkedin.com/in/mansi-saini26/">Contact</a></li>
			</ul>
		</nav>
	</header>
</html>

<!-- TODO: if at about page, highlight about in nav -->
