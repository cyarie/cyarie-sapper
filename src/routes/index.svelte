<style>
	h1, figure, p {
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: lowercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}

	.Work {
		margin-top: 15px;
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<h1>chris yarie dot com</h1>

<div>
	<strong>I am a technical lead at Aledade,</strong> a GV-backed startup in Bethesda, MD.
	<div class="Work">
		<p>
			I'm part of a cross-functional group working to improve Aledade's operational efficiency,
			and work on the software helping the company grow and scale. I also started, organized, and led Aledade's
			first charter guild, which brought together an autonomous group of developers who moved our Gulp-based
			frontend build system over to Webpack.
		</p>
		<p>
			Other work included working as the lead UI/UX developer on a well-tested and designed Flask and AngularJS-based
			application built to help other Aledaders make better decisions around initiative prioritization.
			As part of that, I worked within a cross-functional team that includes designers, data warehouse engineers,
			analysts, and other stakeholders to build value-delivering products. As an outcome of that work,
			we've provided business stakeholders and other decision-makers with high-impact, easy-to-understand views
			into initiative progress that helps us better serve our doctors and
			our patients.
		</p>
	</div>
</div>
<div class="Work">
	<p>Previous work includes doing full-stack development for the Democratic National Committee, where I...</p>
	<ul>
		<li>Built software for using Twitter to track instances of voter suppression and polling-place issues</li>
		<li>Collaborated to design and build an application that enabled over 80,000 voters in Florida to request vote-by-mail ballots via email</li>
		<li>Completely re-engineered the DNC Digital Team's analytics application</li>
	</ul>
	<p>
		I am comfortable working up and down the entire stack -- starting from the front-end, and working all the
		way down to infrastructure planning. I'm also experienced in working with everyone -- from business stakeholders
		to designers -- and in turning user research, mockups, and requirements into usable and performant software.
	</p>
	<p>I am available for political and other non-health care technology consulting.</p>
</div>
