<template>
    <div class="container" id="aboutMe">
        <h1>Augusto A. P. Goncalez</h1>
        <div class="row about-me">
            <div class="col-md-9">
                <p class="lead">Currently working as a Developer Associate at TD. Graduated in the Systems Analyst program 
                    at Sheridan College with high honors (GPA 3.94). Experience working as a developer and eager to learn.
                </p>
            </div>
            <div class="profile-pic col-md-3">
                <img src="./../assets/profilePicture.jpg" alt="my-picture"
                        width="200">
            </div>
        </div>
        <div class="col-12" id="pdf-download">
            <a href="./download/RESUME_AUGUSTO_PERES.pdf" target="_blank" class="download-resume">
                Download Resume (PDF)</a>
        </div>
    </div>
</template>

<script>
export default {
  name: 'AboutMe',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    #aboutMe {
        margin-top: 6em;
    }

    h1 {
        text-align: center;
    }

    .about-me {
        border: 1px solid grey;
        border-radius: 10px;
        padding: 1em;
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
        margin: auto;
        max-height: 200px;
        max-width: 200px;
        width: 100%;
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
