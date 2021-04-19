<template>
    <div class="container" id="contact">
        <h1><img src="../assets/icons8-contact-50.png" alt="work icon">Contact</h1>
        <div class="contact">
            <div class="row">
                <div class="col-md-12 contact-info">
                    <a href="mailto:augustoapg@gmail.com" target="_top">
                        augustoapg@gmail.com</a>
                </div>
            </div>
            <div class="row">
                <div class="col-md-12 social-logos">
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

    .contact-info p, .contact-info a {
        display: block;
        font-size: 1.1em;
        text-align: center;
        width: 100%;
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
        margin: auto;

    }

    .social-logos ul {
        padding: 0;
        margin-top: 1em;
    }

    .social-logos li {
        list-style-type: none;
        margin: 1em 0;
    }
</style>
