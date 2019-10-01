<template>
    <div class="container">
        <h1>Contact</h1>
        <div class="row contact">
            <div class="col-md-6 contact-info">

                <p><img src="../assets/icons8-Email-70.png" 
                        alt="email-icon">
                    <a href="mailto:augustoapg@gmail.com" target="_top">
                        augustoapg@gmail.com</a><p>

                <p><img src="../assets/icons8-Cell Phone-70.png" 
                        alt="email-icon">(289)993-8773</p>


            </div>
            <div class="col-md-6 social-logos">
                <ul>
                    <li><a href="https://github.com/augustoapg" target="_blank">
                            <img src="../assets/github-logo.png" 
                                    alt="github-logo"></a></li>
                    <li><a href="https://www.linkedin.com/in/augustoapg/" 
                            target="_blank">
                            <img src="../assets/linkedin-logo.png" 
                                    alt="linkedin-logo"></a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Contact',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .contact {
        border: 1px solid grey;
        border-radius: 10px;
        padding: 1em;
        vertical-align: middle;
    }

    .contact-info p {
        vertical-align: middle;
        font-size: 1.1em;
        width: 90%;
    }

    .contact-info img {
        width: 10%;
    }

    .social-logos img {
        display: block;
        height: auto;
        max-height: 100px;
        max-width: 200px;
        width: auto;

    }

    .social-logos li {
        list-style-type: none;
    }
</style>
