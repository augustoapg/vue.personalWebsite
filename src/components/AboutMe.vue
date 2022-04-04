<template>
	<div>
		<div class="hello-message">
			<div class="hello-text">
				<h1>Hello!</h1>
				<h1>I am Augusto Peres</h1>
				<h2>I am an Associate Developer at TD Bank</h2>
				<h3 class="scroll-message">
					Scroll down to find out more about me
				</h3>
			</div>
			<canvas class="background"></canvas>
		</div>

		<div class="container" id="aboutMe">
			<h1>
				<img src="../assets/icons8-user-64.png" alt="work icon" />About
				Me
			</h1>
			<div class="row about-me">
				<div class="profile-pic col-md-3">
					<img
						src="./../assets/profilePicture.jpg"
						alt="my-picture"
						width="200"
					/>
				</div>
				<div class="col-md-9">
					<div class="about-me-text">
						<p class="lead">
							I am a Mechanical Engineer who decided to change
							careers because I fell in love with Computer
							Programming. I graduated from the Systems Analyst
							program at Sheridan College in 2019 with high honors
							(GPA 3.94). I have over 3 years of work experience
							with development, and I am always looking for a good
							challenge and for the chance to learn something new!
						</p>
					</div>
				</div>
			</div>
			<div class="col-12" id="pdf-download">
				<a
					href="./download/RESUME_AUGUSTO_PERES.pdf"
					target="_blank"
					class="download-resume"
				>
					Download Resume (PDF)</a
				>
			</div>
		</div>
	</div>
</template>

<script>
import Particles from "particlesjs/dist/particles";
export default {
	name: "AboutMe",
	props: {},
	mounted: function() {
		Particles.init({
			selector: ".background",
			connectParticles: true,
			color: "#00ed00",
		});
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello-message {
	background-color: black;
	width: 100%;
	height: 100vh;
	z-index: 0;
	margin-top: -0.5em;
}
.hello-text {
	font-family: "Noto Sans";
	margin: 0;
	color: white;
	font-size: 4vw;
	text-align: center;
	position: absolute;
	top: 45%;
	z-index: 1;
	width: 100%;
}
.hello-text h1 {
	margin: 0;
	font-size: 2em;
}
.hello-text h2 {
	font-size: 1.1em;
	margin: 0.4em 0;
}
.hello-text .scroll-message {
	font-size: 0.7em;
}

.background {
	height: 100%;
	width: 100%;
	z-index: 0;
}

h1 {
	text-align: center;
}

.about-me {
	padding: 1.3em;
	box-shadow: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px,
		rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;
}

.about-me-text {
	display: table;
	height: 13em;
}

.about-me-text p {
	display: table-cell;
	vertical-align: middle;
}

footer {
	margin: 15px auto;
	padding-right: 10px;
	text-align: right;
}

.profile-pic img {
	border-radius: 20px;
	display: block;
	margin: 1em auto;
	max-height: 200px;
	max-width: 200px;
	width: 100%;
}

.download-resume {
	color: #fff !important;
	text-transform: uppercase;
	text-decoration: none;
	background: #00a300;
	padding: 0.7em;
	border-radius: 30px;
	display: block;
	border: none;
	transition: all 0.4s ease 0s;
	margin: 1.5em auto;
	width: 17em;
	text-align: center;
}

.download-resume:hover {
	background: #00ed00;
	letter-spacing: 1px;
	-webkit-box-shadow: 0px 5px 40px -10px rgba(0, 0, 0, 0.57);
	-moz-box-shadow: 0px 5px 40px -10px rgba(0, 0, 0, 0.57);
	box-shadow: 5px 40px -10px rgba(0, 0, 0, 0.57);
	transition: all 0.4s ease 0s;
}

@media only screen and (min-width: 768px) {
	.hello-message {
		background-color: black;
		width: 100%;
		height: 100vh;
		z-index: 0;
	}

	.hello-text {
		font-family: "Noto Sans";
		margin: 0;
		color: white;
		font-size: 4vw;
		text-align: center;
		position: absolute;
		top: 30%;
		z-index: 1;
		width: 100%;
	}
}
</style>
