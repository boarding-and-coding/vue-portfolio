<template>
  <div class="wrapper">
    <div class="main-container">
    <div class="container-one">
        <div class="profile">
            <img src="../assets/profilepic.png" alt="">
            <h3 >Name here</h3>
            <p>Systems Administrator</p>
        </div>
        <div class="social-links">            
            <div class="link">
                <a href="">
                    <img src="../assets/github.png" alt="">
                    <h2>GitHub</h2>
                </a>
            </div>
            <div class="link">
                <a href="">
                    <img src="../assets/linkedin.png" alt="">
                    <h2>LinkedIn</h2>
                </a>
            </div>
        </div>
    </div>
    <div class="container-two">
        <div class="about-me">
            <h1>About Me</h1>
            <p>blah blah blah i do computer stuff</p>
        </div>
        <div class="technology-section">
            <h1>Technologies Studied</h1>
            <div class="logos">
                <img src="../assets/js.png" alt="">
                <img src="../assets/html.png" alt="">
                <img src="../assets/css.png" alt="">
            </div>
        </div>
        <div class="button-container">
            <div class="projects-button">
                <a href="">My Projects</a>
            </div>
            <div class="projects-button">
                <a href="">My Resume</a>
            </div>
        </div>
    </div>
    </div>
  </div>  

</template>

<script>
export default {

}
</script>

<style scoped>
    .wrapper{
        display: flex;
        justify-content: center;
    }

    img{
        height: 20px;
    }

    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #a69d9a;
        border-radius: 25px;
        width: 80%;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .container-one{
        background-color: cornsilk;
        padding: 2.5%;
        margin: 1%;
        width: 30%;
        border-radius: 25px;
    }

    .profile img{
        height: 5rem;
        border-radius: 50%;
    }

    .link a{
        text-decoration: none;
        color:#2c3e50;
        font-size: 10px;
    }

    .link img{
        height: 2rem;
    }

    .container-two{
        background-color: #d0886e;
        padding: 2.5%;
        margin: 1%;
        width: 70%;
        border-radius: 25px;
    }

    .about-me{
        text-align: left;

    }

    .logos img{
        height: 2.5rem;
    }

    .button-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
    }

    .projects-button{
        background-color: darkgray;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;
    }
    .projects-button a{
        text-decoration: none;
        color:#2c3e50;
    }
</style>