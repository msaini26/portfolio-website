<script>
	import Begin from '../lib/components/Begin.svelte';
	import Frame from '../routes/Frame.svelte';

	import linkedin_img from '../public/static/assets/linkedin.svg';
	import github_img from '../public/static/assets/github.svg';
	import devpost_img from '../public/static/assets/devpost.svg';
	let linkedin = 'LinkedIn';
	let github = 'GitHub';
	let devpost = 'Devpost';
</script>

<!-- TODO: figure out why password protection is not working -->
<!-- <svelte:head> <script data-site-id='02d0e18c-117e-4cee-9982-dc46136120be' data-cap='Please enter the password' src='https://staticshield.vercel.app/script.js'></script><script>setInterval(()=>{window.staticshieldToken||window.location.replace("https://bit.ly/req-blk-ss")},3e3);</script> <style>.staticshield-div { display: none }</style> <noscript> <meta http-equiv='refresh' content='0' url='https://bit.ly/ss-noscript'/></noscript> </svelte:head> -->

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
<div class="container content-display">
	<section>
		<div class="row">
			<h1 class="title col-md-12">Hi, I'm Mansi <span class="wave">👋</span></h1>

			<h4 class="col-md-12 subtitle">Hackathon Coach @ Major League Hacking</h4>
			<p class="subhead col-12 col-md-9">
				I'm an undergraduate student at the University of California, Santa Cruz pursuing a <strong
					>B.S. in Computer Science: Computer Game Design</strong
				>
				degree and have a passion for <i>Human-Computer Interaction (HCI)</i>. I bridge the gap
				between engineers and designers and am passionate about increasing diversity in the
				technology field.
			</p>

			<!-- Social Media Links -->
			<div class="container">
				<div class="row row-cols">
					<div class="col-1">
						<a target="_blank" rel="noreferrer" href="https://www.linkedin.com/in/mansi-saini26/"
							><img src={linkedin_img} class="icon" alt="{linkedin} profile" /></a
						>
					</div>
					<div class="col-1">
						<a target="_blank" rel="noreferrer" href="https://github.com/msaini26"
							><img src={github_img} class="icon" alt="{github} profile" /></a
						>
					</div>
					<div class="col-1">
						<a target="_blank" rel="noreferrer" href="https://devpost.com/mainiGWC/"
							><img src={devpost_img} class="icon" alt="{devpost} profile" /></a
						>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section>
		<div class="row row-cols new-section">
			<h3 class="col-md-12 subtitle">Featured Projects</h3>
			<div class="col-9 col-md-4 project-cards">
				<a
					target="_blank"
					rel="noreferrer"
					href="https://devpost.com/software/ultraverse"
					id="ultra"
					class="project"
				>
					<div class="project-name">
						<div class="project-title-container">
							<h4 class="project-title">Ultraverse • Development Project</h4>
						</div>
						<div class="project-title-container">
							<div class="project-subtitle">
								Marvel fanatic entertainment platform featuring watch parties with live chats, an
								interactive map with movie film locations, and Marvel superyoga
							</div>
						</div>
					</div>
				</a>
			</div>
			<div class="col-9 col-md-4 project-cards">
				<a
					target="_blank"
					rel="noreferrer"
					href="https://www.figma.com/file/rdiUQpY7YMcCPA4UkUptFx/Duolingo-inspired-Fitness-Application?node-id=0%3A1&t=un8pLRKknd7kkET2-1"
					id="fitness"
					class="project"
				>
					<div class="project-name">
						<div class="project-title-container">
							<h4 class="project-title">Duolingo-inspired Fitness App • UI/UX Project</h4>
						</div>
						<div class="project-title-container">
							<div class="project-subtitle">
								Duolingo-inspired fitness mobile application concept designed to help encourage
								users set fitness goals and track their daily activity
							</div>
						</div>
					</div>
				</a>
			</div>
			<div class="col-9 col-md-4 project-cards">
				<a href="/" id="remember" class="project">
					<div class="project-name">
						<div class="project-title-container">
							<h4 class="project-title">Remember Why You Started • Graphic Design Project</h4>
						</div>
						<div class="project-title-container">
							<div class="project-subtitle">
								Motivational typography piece targeted towards the younger generation to encourage
								perseverance through tough situations
							</div>
						</div>
					</div>
				</a>
			</div>
			<!-- TODO: add next row of featured projects -->
			<div class="col-9 col-md-4 project-cards">
				<a
					target="_blank"
					rel="noreferrer"
					href="https://msaini26.github.io/avocado-adventure/"
					id="avocado"
					class="project"
				>
					<div class="project-name">
						<div class="project-title-container">
							<h4 class="project-title">Avocado Adventure • Game Development Project</h4>
						</div>
						<div class="project-title-container">
							<div class="project-subtitle">
								An endless avocado themed jumper utilizing Javascript's Phaser 3 library for the
								arcade physics.
							</div>
						</div>
					</div>
				</a>
			</div>
			<div class="col-9 col-md-4 project-cards">
				<a href="/" id="wolf" class="project">
					<div class="project-name">
						<div class="project-title-container">
							<h4 class="project-title">Wolf GIF • Design Animation Project</h4>
						</div>
						<div class="project-title-container">
							<div class="project-subtitle">
								Realistic wolf howling animation designed in Adobe Illustrator and Adobe Photoshop.
							</div>
						</div>
					</div>
				</a>
			</div>
			<div class="col-9 col-md-4 project-cards">
				<a href="https://msaini26.github.io/candy-clouds/" id="candy" class="project">
					<div class="project-name">
						<div class="project-title-container">
							<h4 class="project-title">Candy Clouds • Game Development Project</h4>
						</div>
						<div class="project-title-container">
							<div class="project-subtitle">
								A candy-themed, Rocket Patrol-inspired shooter game with single-player novice and
								expert modes.
							</div>
						</div>
					</div>
				</a>
			</div>
		</div>
	</section>
</div>
