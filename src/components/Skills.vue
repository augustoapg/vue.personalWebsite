<template>
    <div class="container" id="skills">
        <h1>Skills</h1>

        <div class="row">
            <div class="col-md-6">
                <h4 class="resume-session-title">Development Skills</h4>
                <ul class="activity-desc">
                    <li>HTML, CSS, JavaScript, Bootstrap</li>
                    <li>Angular, Vue.js, jQuery, jQuery Mobile, NodeJS</li>
                    <li>JavaSE, J2EE, Spring Boot</li>
                    <li>Python, Tkinter, matplotlib</li>
                    <li>GoLang</li>
                    <li>C#, .NET Framework, ASP.NET</li>
                    <li>SQL, MySQL, SQL Server, PostgreSQL, MongoDB</li>
                    <li>Android development using JAVA</li>
                    <li>PHP, Wordpress</li>
                    <li>REST, JSON, XML, AJAX</li>
                    <li>Cordova</li>
                </ul>
            </div>

            <div class="col-md-6">
                <h4 class="resume-session-title">System Analysis / Project Management</h4>
                <ul class="activity-desc">
                    <li>Software Development Life Cycle (SDLC)</li>
                    <li>SCRUM, Agile Methodologies</li>
                    <li>Unified Modeling Language (UML)</li>
                    <li>Lean Six Sigma</li>
                </ul>

                <h4 class="resume-session-title">Other Skills</h4>
                <ul class="activity-desc">
                    <li>Docker, Vagrant</li>
                    <li>Git</li>
                    <li>Selenium, Codeception, Bamboo</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Skills',
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

    .education-block {
        margin: 1em 0;
        text-align: center
    }

    .extra-details {
        margin: 0;
        font-style: italic;
    }
</style>
