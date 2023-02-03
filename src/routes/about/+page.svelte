<script>
	import Begin from '../../lib/components/Begin.svelte';
	import Frame from '../../routes/Frame.svelte';
	import headshot from '../../public/static/assets/headshot2.jpg';

	let about_pic = 'about me picture';
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
<!-- TODO: #4 content included + photo -->

<!-- About/Bio -->
<div class="container content-display">
	<section>
		<div class="row row-cols new section">
			<div class="col-md-6">
				<h3 class="subtitle">About Me</h3>
				<p class="subhead">
					I'm an undergraduate student at the University of California, Santa Cruz pursuing a <strong
						>B.S. in Computer Science: Computer Game Design</strong
					>
					degree and have a passion for <i>Human-Computer Interaction (HCI)</i>. I bridge the gap
					between engineers and designers and am passionate about increasing diversity in the
					technology field.
				</p>
			</div>
			<div class="col-md-2" />
			<!-- TODO: contain entire line vs empty div -->
			<div class="col-md-4 new-section">
				<img id="about-headshot" src={headshot} alt={about_pic} />
			</div>
		</div>
	</section>

	<div class="container content-display">
		<section>
			<div class="row row-cols new section">
				<div class="col-md-6">
					<h3 class="subtitle">Features</h3>
				</div>
				<div class="col-md-2" />
				<div class="col-md-4 new-section">
					<p>insert article features here</p>
				</div>
			</div>
		</section>
	</div>
</div>


