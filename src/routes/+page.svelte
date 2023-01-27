<script>
	import Begin from '../lib/components/Begin.svelte';
	import Frame from '../routes/Frame.svelte';
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
		<!-- Favicon -->
		<link rel="icon" href="../src/favicon.png" />

		<!-- Social Media Icons -->
		<link
			rel="stylesheet"
			href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
		/>
	</head>
</html>

<!-- insert SEO title -->
<Begin />

<!-- insert header and footer -->
<Frame />

<!-- About/Bio -->
<div class="container bio">
	<div class="row">
		<h1 class="title col-md-12">Hi, I'm Mansi</h1>
		<h4 class="col-md-12 subtitle">Hackathon Coach @ Major League Hacking</h4>
		<p class="subhead col-12 col-md-9">
			I'm an undergraduate student at the University of California, Santa Cruz pursuing a <strong
				>B.S. in Computer Science</strong
			> degree and have a passion for Human-Computer Interaction (HCI). I bridge the gap between engineers
			and designers and am passionate about increasing diversity in the technology field.
		</p>

		<div class="container">
			<div class="row row-cols">
				<div class="col-1">
					<a href="https://www.linkedin.com/in/mansi-saini26/"
						><img class="icon" alt="linkedin" src="../src/static/assets/linkedin.svg" /></a
					>
				</div>
				<div class="col-1">
					<a href="https://github.com/msaini26"
						><img class="icon" alt="github" src="../src/static/assets/github.svg" /></a
					>
				</div>
				<div class="col-1">
					<a href="https://devpost.com/mainiGWC/"
						><img class="icon" alt="devpost" src="../src/static/assets/devpost.svg" /></a
					>
				</div>
			</div>
		</div>
		<!-- Social Media Links -->
	</div>
</div>
