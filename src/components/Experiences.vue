<template>
	<div class="container" id="experiences">
		<h1>
			<img
				src="../assets/icons8-work-64.png"
				alt="work icon"
			/>Experiences
		</h1>

		<div class="row">
			<div class="col-12">
				<h3>Software Engineer (Associate Engineer II)</h3>
				<p class="location">TD</p>
				<p class="date">(01/2022 - present)</p>
				<ul class="activity-desc">
					<li>
						Responsible for the creation of an application for
						bankers that saves, loads, displays and exports data. In
						charge of the Front-end
					</li>
					<li>
						Participated in decisions on data structure,
						architecture and code standards
					</li>
					<li>
						Work closely with DevOps to assist with the deployment
						in all environments
					</li>
					<li>
						Use Figma and Jira to analyze design and business
						requirements
					</li>
					<li>
						<i>Technologies Used:</i> React, TypeScript, SCSS,
						Python, Flask, MySQL, Git
					</li>
				</ul>
			</div>
			<div class="col-12">
				<h3>Developer Associate</h3>
				<p class="location">TD</p>
				<p class="date">(01/2020 - 12/2021)</p>
				<ul class="activity-desc">
					<li>
						<b>Corporate Investment Banking</b> - (07/2021 -
						12/2021)
					</li>
					<ul class="rotation">
						<li>
							Assist with development of interactive internal apps
							for bankers
						</li>
						<li>
							Demoed applications to executives and Product Owners
						</li>
						<li>
							Researched Glue42 API to implement requirements from
							Product Owner
						</li>
						<li>
							<i>Technologies Used:</i> React, Python, Flask,
							Tailwind CSS, MySQL, Git, Glue42, AG-Grid
						</li>
					</ul>
					<li>
						<b>Central Innovation Agency (CIA)</b> - (01/2021 -
						06/2021)
					</li>
					<ul class="rotation">
						<li>
							Supported and created new features for TD Gigs, an
							internal platform for short term assignments
						</li>
						<li>Developed scripts for spreadsheet automation</li>
						<li>
							Implemented POCs related to Distribution Lists
							listed in Active Directory (AD)
						</li>
						<li>
							Participated and helped organize One Day Builds,
							which were full days of coding to create a POC with
							business value
						</li>
						<li>
							<i>Technologies Used:</i> Angular, NodeJS, Python,
							MySQL, Git
						</li>
					</ul>
					<li>
						<b>Deposit Accounting Systems (DAS)</b> - (01/2020 -
						12/2020)
					</li>
					<ul class="rotation">
						<li>Wrote scripts for data retrieval and automation</li>
						<li>Assisted with the suport of batch jobs</li>
						<li>
							Responsible for package handling, helping developers
							to transfer their changes from dev to production
							environments using Endevor and ServiceNow
						</li>
						<li><i>Technologies Used:</i> Python, VBA, SAS, JCL</li>
					</ul>
				</ul>
			</div>
			<div class="col-12">
				<h3>Python Developer Research Assistant</h3>
				<p class="location">Sheridan College</p>
				<p class="date">(09/2019 - 12/2019)</p>
				<ul class="activity-desc">
					<li>
						Responsible for the design and development of a
						Dashboard for data visualization in real time
					</li>
					<li>Create a mobile app version of the Dashboard</li>
					<li>
						<i>Technologies Used:</i> Python, Tkinter, MySQL,
						Android (Java)
					</li>
				</ul>
			</div>
			<div class="col-12">
				<h3>Jr. Web Developer and QA Analyst</h3>
				<p class="location">Government of Ontario</p>
				<p class="date">(05/2019 - 08/2019)</p>
				<p class="date">(09/2018 - 12/2018)</p>
				<ul class="activity-desc">
					<li>
						Worked in an Agile based team for the Ontario Public
						Service intranet
					</li>
					<li>
						Implemented new features and assisted for most
						components of the website
					</li>
					<li>Developed automated test scripts</li>
					<li>
						<i>Technologies Used:</i> Vue, Go, PHP, Selenium,
						Bamboo, Docker, Vagrant
					</li>
				</ul>
			</div>
			<div class="col-12">
				<h3>Co-op Developer</h3>
				<p class="location">HitGrab Game Labs</p>
				<p class="date">(01/2018 - 04/2018)</p>
				<ul class="activity-desc">
					<li>Develop a multiplayer word game prototype</li>
					<li>
						<i>Technologies Used:</i> JavaScript, jQuery, NodeJS,
						MongoDB
					</li>
				</ul>
			</div>
			<div class="col-12">
				<h3>Peer Assisted Learning Leader</h3>
				<p class="location">Sheridan College</p>
				<p class="date">(09/2017 - 12/2017)</p>
				<ul class="activity-desc">
					<li>
						Plan, prepare and lead one hour sessions weekly on
						computer math where the most important topics given in
						class are revisited and practiced
					</li>
					<li>
						Encourage class’s participation and guide the students
						towards the solution
					</li>
				</ul>
			</div>
			<div class="col-12">
				<h3>Manufacture Engineer Intern</h3>
				<p class="location">EATON Hydraulics</p>
				<p class="date">(01/2017 - 12/2017)</p>
				<ul class="activity-desc">
					<li>
						Worked on a team project to develop a new data flux for
						the company's scrap, reducing the time needed for
						analysis and increasing the data reliability
					</li>
					<li>
						Developed an Excel program with VBA to make it easier
						for the employees to input the production data, as well
						as increasing the data reliability and facilitating the
						analysis
					</li>
					<li>
						Conducted and participated on 5S events to organize and
						clean properly several work stations
					</li>
					<li>
						Presented to the company once a week advice and news
						about health and safety
					</li>
				</ul>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: "Experiences",
	props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
	text-align: center;
	background-color: rgb(240, 240, 243);
}

.location {
	font-weight: bold;
	margin: 0;
}

.date {
	margin: 0;
}

.rotation,
.activity-desc {
	margin: 1em 0;
}
</style>
