<template>
    <div class="container" id="experiences">
            <h1><img src="../assets/icons8-work-64.png" alt="work icon">Experiences</h1>
        <div class="col-12" id="pdf-download">
            <a href="./download/RESUME_AUGUSTO_PERES.pdf" target="_blank" class="download-resume">
                Download Resume (PDF)</a>
        </div>

        <div class="row">
            <div class="col-12">
                <h3>Python Developer Research Assistant</h3>
                <p class="location">Sheridan College</p>
                <p class="date">(09/2019 - present)</p>
                <ul class="activity-desc">
                    <li>Responsible for assisting in the design and development of a Dashboard for data visualization in real time</li>
                    <li>Developing dashboard using Python with the GUI created with Tkinter.</li>
                </ul>
            </div>
            <div class="col-12">
                <h3>Jr. Web Developer and QA Analyst</h3>
                <p class="location">Government of Ontario</p>
                <p class="date">(05/2019 - 08/2019)</p>
                <p class="date">(09/2018 - 12/2018)</p>
                <ul class="activity-desc">
                    <li>Worked in an Agile based team for the Ontario Public Service intranet, which is used by around 60,000 public employees.</li>
                    <li>Implemented new features and fixed bugs for most components of the website, which included front-end created in Vue, back-end using PHP with a customized Wordpress, and an API created using Go</li>
                    <li>Worked with Docker and Vagrant for creating and debugging code in a local environment</li>
                    <li>Developed automated test scripts using Selenium, Codeception and Bamboo</li>
                </ul>
            </div>
            <div class="col-12">
                <h3>Co-op Developer</h3>
                <p class="location">HitGrab Game Labs </p>
                <p class="date">(01/2018 - 04/2018)</p>
                <ul class="activity-desc">
                    <li>Developed front and back end of a multiplayer word game prototype using JavaScript, jQuery, NodeJS and Socket.io.</li>
                    <li>Organized scheduled tests and properly documented the results in order to improve the prototype based on the feedback provided.</li>
                    <li>Responsible for organizing the project and delivering the results within the due date.</li>
                </ul>
            </div>
            <div class="col-12">
                <h3>Peer Assisted Learning Leader</h3>
                <p class="location">Sheridan College</p>
                <p class="date">(09/2017 - 12/2017)</p>
                <ul class="activity-desc">
                    <li>Plan, prepare and lead one hour sessions 
                                weekly on computer math where the most 
                                important topics given in class are 
                                revisited and practiced.</li>
                    <li>Encourage class’s participation and guide 
                        the students towards the solution.</li>
                </ul>
            </div>
            <div class="col-12">
                <h3>Manufacture Engineer Intern</h3>
                <p class="location">EATON Hydraulics</p>
                <p class="date">(02/2017 - 08/2017)</p>
                <ul class="activity-desc">
                    <li>Worked on a team project to develop a new 
                                data flux for the company's scrap, reducing 
                                the time needed for analysis and increasing 
                                the data reliability</li>
                    <li>Interviewed the machine operators in order 
                        to develop an Excel program with VBA to make
                        it easier for the employees to input the
                        production data, as well as increasing the 
                        data reliability and facilitating the 
                        analysis.</li>
                    <li>Conducted and participated on 5S events to 
                        organize and clean properly several work 
                        stations.</li>
                    <li>Presented to the company once a week advice 
                        and news about health and safety.</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Experiences',
  props: {
    
  }
}
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

    .download-resume {
        color: #fff !important;
        text-transform: uppercase;
        text-decoration: none;
        background: #4441eb;
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
        background: #4696ff;
        letter-spacing: 1px;
        -webkit-box-shadow: 0px 5px 40px -10px rgba(0,0,0,0.57);
        -moz-box-shadow: 0px 5px 40px -10px rgba(0,0,0,0.57);
        box-shadow: 5px 40px -10px rgba(0,0,0,0.57);
        transition: all 0.4s ease 0s;
    }
</style>
