<template>
    <div class="container">
        <h1>About Me</h1>
        <div class="row about-me">
            <div class="col-md-9">
                <p class="lead">Currently enrolled in the Systems Analyst program at Sheridan College on my last 
                    term with excellent performance (GPA 3.94). Also working part time as a Python Developer 
                    Research Assistant at Sheridan College. Experience working as a developer and eager to learn. 
                    Presently seeking a full-time position after graduation where I can keep improving my 
                    skills and develop my career.
                </p>
            </div>
            <div class="profile-pic col-md-3">
                <img src="../assets/profilePicture.jpg" alt="my-picture"
                        width="200">
            </div>
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

    h1 {
        margin-top: 2em;
        text-align: left;
    }

    .profile-pic img {
        border-radius: 20px;
        display: block;
        margin: auto;
        max-height: 200px;
        max-width: 200px;
        width: 100%;
    }
</style>
