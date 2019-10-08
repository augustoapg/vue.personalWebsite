<template>
    <div class="container" id="education">
        <h1>Education</h1>

        <div class="row">
            <div class="col-12 education-block">
                <h3>Systems Analyst Co-op Program</h3>
                <p class="location">Sheridan College</p>
                <p class="date">(01/2017 - present)</p>
                <p class="extra-details">3.94 GPA</p>
                <p class="extra-details">Expected graduation in 12/2019</p>
            </div>

            <div class="col-12 education-block">
                <h3>Mechanical Engineering</h3>
                <p class="location">UNESP - Guaratingueta, SP/Brazil </p>
                <p class="date">(01/2010 - 12/2016)</p>
                <p class="extra-details">Bachelors Degree</p>
            </div>

            <div class="col-12 education-block">
                <h3>Mechanical Eng. (Scholarship Program)</h3>
                <p class="location">University of Guelph</p>
                <p class="date">(01/2014 - 12/2014)</p>
            </div>

            <div class="col-12 education-block">
                <h3>Lean Six Sigma - Black Belt Training</h3>
                <p class="location">Dinamica Treinamentos - Guaratingueta, SP/Brazil</p>
                <p class="date">(120 hours course)</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Education',
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
