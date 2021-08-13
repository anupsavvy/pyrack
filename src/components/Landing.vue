<template>
  <div>
    <v-toolbar id="titlebar">
      <v-toolbar-title><img src="../assets/icon.png" height="40"></v-toolbar-title>
    </v-toolbar>
    <v-content>
      <!-- Intro section starts -->
      <section>
        <v-container class="container--style">
          <v-row justify="center">
            <v-col md="8" class="text-center">
              <v-row justify="right" no-gutters>
                <v-col cols="3" offset="7" align="left">
                  <h3 id="name">Anup Sawant's</h3>
                </v-col>
              </v-row>
              <img id="logo" src="../assets/logo2.jpg" alt="">
              <p class="text-center my-5" id="intro-text">I help my clients utilize their data and improve on their productivity on a range of online and offline products based on Artificial Intelligence and Graph Theory. You can find my past affiliations <a href="https://www.linkedin.com/in/anupsawant/" target="_blank">here.</a> For the last few years, I've worked full-time remotely from India (mostly for clients from the USA). A unique experience with lots of video calls, messages and nice clients.</p>
            </v-col>
          </v-row>
        
        </v-container>
      </section>
      <!-- Intro section ends -->
        
      <!-- Ways I can help you starts -->
      <section id="help">
                  <v-card
              class="mx-5 my-6 help-cards"
              flat
            >
              <h1 class="text-left mx-8 my-6 large-text">Ways I can help you</h1>
              <v-container fluid class="mx-8">
                <v-row justify="center" dense>
                  <v-col
                   cols="4"
                    lg="2"
                    md="4"
                  >
                    <v-card flat height="400">
                      <v-img
                        src="../assets/consulting.jpg"
                        class="align-end white--text card-image"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                      >
                        <v-card-title id="card-title"><span>AI consulting</span></v-card-title>
                      </v-img>
                      <v-card-text id="card-text">
                        <span>Figure out laborious and repitative tasks in your business domain and help your existing IT product/staff leverage the power of AI. This gives a good start to assess AI solution needs.</span>
                      </v-card-text>
                    </v-card>
                  </v-col>
                  <v-col
                    
                 cols="4"
                    lg="2"
                    md="4"
                  >
                    <v-card flat height="400">
                      <v-img
                        src="../assets/data-analysis.jpg"
                        class="align-end white--text card-image"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                      >
                        <v-card-title id="card-title"><span>Data analysis</span></v-card-title>
                      </v-img>
                      <v-card-text id="card-text">
                        <span>Utilize your digital data to derive patterns and reveal insights that could help understand your customers and improve your profit.</span>
                      </v-card-text>
                    </v-card>
                  </v-col>
                  <v-col
                    
                  cols="4"
                    lg="2"
                    md="4"
                  >
                    <v-card flat height="400">
                      <v-img
                        src="../assets/plug.jpg"
                        class="align-end white--text card-image"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                      >
                        <v-card-title id="card-title"><span>AI services</span></v-card-title>
                      </v-img>
                      <v-card-text id="card-text">
                        <span>I can raise custom AI endpoints that your existing application can consume and get smarter at performing business tasks.</span>
                      </v-card-text>
                    </v-card>
                  </v-col>
                   <v-col
                   cols="4"
                    lg="2"
                    md="4"
                  >
                    <v-card flat height="400">
                      <v-img
                        src="../assets/solution.jpg"
                        class="align-end white--text card-image"
                        gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                        height="200px"
                      >
                        <v-card-title id="card-title"><span>Entire solution</span></v-card-title>
                      </v-img>
                      <v-card-text id="card-text">
                        <span>I can develop an end-to-end (backend, frontend, AI models) web application for you thats scalable, portable across platforms and, most importantly, designed according to your needs.</span>
                      </v-card-text>
                    </v-card>
                  </v-col>
                </v-row>
              </v-container>
            </v-card>
        <v-card
              id="testimonial-section"
              class="mx-5 my-6 help-cards"
              flat
            >
              <h1 class="text-left mx-8 my-6 large-text" id="keypoints">From big to small clients, two things I always promise</h1>
              <v-row justify="center" class="my-8" dense>
                <v-col
                    align="right"
                    md="5"
                    sm="12"
                >
                  <h2 align="right"> <v-avatar
                      left
                      color="#33587b"
                      size="42"
                  >
                  <span class="white--text">1</span>
                  </v-avatar>  <span class="promise--text">A healthy work relationship</span></h2>
                  <p id="promise-content" align="right">No dramas or difficult work relationships. I'm here to make your life easier, solve problems and help you grow your business.</p>
                </v-col>
                <v-col cols="1" class="justify-center d-none d-md-flex">
                    <v-divider
                      vertical
                    ></v-divider>
                </v-col>
                <v-col
                  align="left"
                  md="5"
                  sm="12"
                >
                <h2> <v-avatar
                        left
                        color="#33587b"
                        size='42'
                      >
                        <span class="white--text">2</span>
                      </v-avatar>  <span class="promise--text">Work that you will love</span></h2>
                <p id="promise-content">This is what I love to do, so I’ll make sure you are happy with the results. We’ll work as a team and we’ll get there!</p>
                </v-col>
              </v-row>
              
            </v-card>

                <v-row justify="center" dense>
                  <v-col
                    class="mx-3"
                    cols="10"
                    md="10"
                    xs="12"
                  >
      <v-card id="testimonials" class="mx-5 my-3 help-cards" flat>
        <img src="../assets/keyboard.jpg" alt="" id="keyboard-img">
        <v-card id="first-testimonial" elevation="20">
          <v-avatar size="48" class="timage">
            <img src="../assets/zach.jpeg" alt="">
          </v-avatar>
          <v-card-text id="card-text">
            "Anup is both a skilled developer and excellent co-worker. He has worked on a variety of web applications while with our group, handling both back-end development and front-end development on these projects...."
          </v-card-text>
          <a class="text-center ta" href="https://www.linkedin.com/in/anupsawant/" target="_blank">Read on LinkedIn</a>
          <v-card-actions id="card-text">
            <h5 class="names"><span>Zachary Gibson - <strong class="designation">PhD Student at Northwestern University</strong></span></h5>
          </v-card-actions>
        </v-card>
        <v-card id="second-testimonial" elevation="20">
          <v-avatar size="48" class="timage">
            <img src="../assets/sophia.jpeg" alt="">
          </v-avatar>
          <v-card-text id="card-text">
            "Anup is a great programmer, and he is great at Java even when it's embedded in another software (AnyLogic). He is also very patient and listens well to what the project is trying to accomplish..."
          </v-card-text>
          <a class="text-center ta" href="https://www.linkedin.com/in/anupsawant/" target="_blank">Read on LinkedIn</a>
          <v-card-actions id="card-text">
            <h5 class="names"><span>Sophia Sullivan - <strong class="designation">Senior Director of Data Science at Integra Credit</strong></span></h5>
          </v-card-actions>
        </v-card>
        <v-card id="third-testimonial" elevation="20">
          <v-avatar size="48" class="timage">
            <img src="../assets/hugh.jpeg" alt="">
          </v-avatar>
          <v-card-text id="card-text">
            "If I were stranded on a desert isle with my only hope of escape being to pair program my way to rescue, I would take Anup with me. Anup would be an asset to any endeavor..."
          </v-card-text>
          <a class="text-center ta" href="https://www.linkedin.com/in/anupsawant/" target="_blank">Read on LinkedIn</a>
          <v-card-actions id="card-text">
            <h5 class="names"><span>Hugh Devlin - <strong class="designation">Senior Computer Scientist</strong></span></h5>
          </v-card-actions>
        </v-card>

      </v-card>
                  </v-col>
                </v-row>


            
      </section>
      <!-- Ways I can help you ends -->
    <!-- ML steps -->
      <section id="ml-steps">
        <v-card
              class="mx-5 my-6"
              id="ml-step-card"
              flat
            >
              <h1 class="text-left mx-8 my-6 large-text" id="keypoints">And that's how a typical AI product building process would work</h1>
              <v-row class="my-3" justify="center">
                <v-col cols="12" md="12" class="text-center">
                  <img id="steps" src="../assets/mlsteps.png" alt="">
                </v-col>
              </v-row>
        </v-card>
      </section>
      <!-- ML steps end -->
      <!-- Ask -->
      <section id="ml-steps">
        <v-card
              class="mx-5 my-6"
              id="ml-step-card"
              flat
            >
              <h1 class="text-left mx-8 my-6 large-text" id="keypoints">Hey Google!! call Anup....</h1>
              <v-row class="my-5" justify="center">
                <v-col cols="5" md="5" class="text-center">
                    <v-expansion-panels flat focusable light hover>
                      <v-expansion-panel class="epanel">
                        <v-expansion-panel-header id="card-text">
                          <h3>Do you charge per hour or per project rate?</h3>
                        </v-expansion-panel-header>
                        <v-expansion-panel-content class="answer">
                          I prefer to charge per project. It works better for me to set a price and not count hours as buidling a great product can mean putting lots of hours anyway :)
                        </v-expansion-panel-content>
                      </v-expansion-panel>
                      <v-expansion-panel class="epanel">
                        <v-expansion-panel-header id="card-text">
                          <h3>We are in different time zone than yours. Is that ok?</h3>
                        </v-expansion-panel-header>
                        <v-expansion-panel-content class="answer">
                          Yes. Around 90% of my clients are from the US, so I'm very used to working with teams that are in different time-zones than mine. I'm happy to adapt.
                        </v-expansion-panel-content>
                      </v-expansion-panel>
                      <v-expansion-panel class="epanel">
                        <v-expansion-panel-header id="card-text">
                          <h3>Are we going to have daily calls?</h3>
                        </v-expansion-panel-header>
                        <v-expansion-panel-content class="answer">
                          It's up to you! Some clients prefer to have daily catchups, others weekly meetings. The important thing is that you feel comfortable with the way we work together.
                        </v-expansion-panel-content>
                      </v-expansion-panel>
                      <v-expansion-panel class="epanel">
                        <v-expansion-panel-header id="card-text">
                          <h3>Do you have your own team?</h3>
                        </v-expansion-panel-header>
                        <v-expansion-panel-content class="answer">
                          My teams are entirely according to the project need. Depending upon the assignment, I work with existing teams of my clients or raise an independant team as per the demand of the assignment.
                        </v-expansion-panel-content>
                      </v-expansion-panel>
                    </v-expansion-panels>
                </v-col>
                <v-col cols="4" md="4" class="text-center">
                  <img id="google" src="../assets/google.jpg" alt="">
                </v-col>
              </v-row>
        </v-card>
      </section>
      <!-- Ask end -->
       <!-- Contact -->
      <section id="contact">
        <v-card
              class="mx-5 my-5"
              id="contact-card"
              flat
            >
            <v-row justify="center">
              <v-col cols="12" md="12" class="text-center">
                <h1 class="my-6 contact-heading">That's it! Now its your turn to say hi.</h1>
                <h2 class="my-3 white--text">I'd love to hear from you - ANUP@PYRACK.COM</h2>
                <h3 class="white--text">Business executives: Rahul Suryawanshi - USA (rahul@pyrack.in), Santosh Modi - India (santosh@pyrack.com)</h3>
                <span my-8>...</span>
              </v-col>
            </v-row>
        </v-card>
      </section>
      <!-- Contact -->
          </v-content>
   
  </div>
</template>

<script>
  export default {
    name: 'Landing',

    data: () => ({
    }),
  }
</script>
<style scoped>
  #titlebar {
      -webkit-user-select: none;
      -webkit-app-region: drag;
      position: absolute;
      left: 0px;
      top: 0px;
      width: 100%;
      height: 30px;
      background-color: #33587b;
    } 
  .container--style{
    margin-top:20px;
    padding:5em 0 5em 0;
    font-family: 'Comfortaa', cursive;
    color: #434647;
  }
  #past-affiliations{
    background-color: white;
    font-family: 'Comfortaa', cursive;
    color: #434647;
  }
  #logo{
    max-width: 60% !important;
  }
  #name{
    margin-top:32px;
  }
  #help{
    font-family: 'Comfortaa', cursive;
    height:2200px !important;
    background-color: #E3ECF2;
    padding-top:20px;
  }
  #ml-steps{
    background-color: white;
    font-family: 'Comfortaa', cursive;
  }
  #intro-text{
    font-family: 'Comfortaa', cursive;
    font-weight: 700;
    font-size: large;
  }
  .help-cards{
    background-color: #E3ECF2 !important;
    color: #434647;
    padding-top: 2rem;
  }
  #card-title{
    font-weight: 700;
    color:white;
  }
  #card-text{
    font-weight: 600;
    color: #434647;
  }
  .large-text{
    font-size: 2rem;
    color: #434647;
  }
  #keypoints{
    width:600px;
  }
  h2{
    color: #434647;
  }
  #promise-content{
    width:400px;
    margin-top:20px;
    font-weight:600;
  }
  #testimonials{
    position: relative;
    height: 400px !important;
    margin-top: 15rem !important;
    padding-top: 5rem;
    overflow: visible;
  }
  #keyboard-img{
    opacity: 0.5;
    position: absolute;
    left:0;
    top:0;
    width:100%;
    height:auto;
  }
  #first-testimonial{
    position:absolute;
    left:250px;
    top:-100px;
    width:300px;
    padding:10px;
  }
   #second-testimonial{
    position:absolute;
    left:650px;
    top:-25px;
    width:300px;
    padding:10px;
  }
  #third-testimonial{
    position:absolute;
    left:500px;
    top:400px;
    width:300px;
    padding:10px;
  }
  .timage{
    margin-top:40px !important;
    margin-bottom:20px;
    margin-left:40%;
  }
  .ta{
    margin-left:25%;
  }
  .names{
    margin-top:25px;
  }
  .designation{
    font-weight: 1200;
  }
  #ml-step-card{
    margin-top: 5rem !important;
    padding-top: 20px;
  }
  #steps{
    margin-top: 3rem;
    width:80%;
  }
  #google{
    opacity:0.8;
    width: 100%;
    height: 100%;
    box-shadow: 0 0 8px 8px white inset;
  }
  .epanel{
    padding-top:0.5rem;
    padding-bottom:0.5rem;
  }
  #contact{
    background-color: #33587b;
    padding-top:5rem;
    padding-bottom:0px !important;
    margin-bottom:0px !important;
  }
  .contact-heading{
    font-size: 4rem;
    line-height: 0.9em;
    color: white;
  }
  #contact-card{
    background-color: #33587b;
  }
  .card-image{
    opacity: 0.9;
  }
  .answer{
    font-weight: 800;
    margin-top:20px;
  }
  #footer{
    margin-top:0px !important;
    padding-top:0px !important;
  }
  #testimonial-section{
    margin-bottom:10rem;
  }
</style>