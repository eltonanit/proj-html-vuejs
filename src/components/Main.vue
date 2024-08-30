<template>

    <div class="bg-blu1">
        <div class="container">
            <div class="row">
                <div class="col-12 text-center text-white">  
                 <h1>Learn At Your Ow---- Pace!</h1>
            <p>Get teamed up with people of the same will</p>
            <button class="cta-button">Get Started For Free</button>
                </div>
            </div>
        </div>

        <!-- SEZIONE 1  BLU-->
         <section class="hero text-white mt-3">
           
           

 </section> 
 <!-- IMMAGINI 1 -->
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-md-3  image-wrappe">
                    <img src="../assets/img/home-6-hero-left-person.png" alt="" class="img-fluid side-image-1">
                </div>
                <div class="col-md-6  image-wrappe">
                    <img src="../assets/img/video-screen (1).png" alt="dark" class="img-fluid">
                </div>
                <div class="col-md-3  image-wrapper">
                    <img src="../assets/img/home-6-hero-right-person.png" alt="" class="img-fluid side-image right-image">
                </div>
                </div>

                 <!-- IMMAGINI 1 -->
                  <div class="bg-white">


                  </div>
                <div class="container">
                    <div class="row">
                         <div class="col-6">
 
                        </div>                        
                    </div>
                </div>
            </div>
        </div>
     


    <!-- SEZIONE 2-A  WHITE-->
    <div class="text-dark">
        <div class="container">
            <div class="row">
                <div class="col-12 text-center">
                    <section class="hero">
                        <h3>Let passion and determination be the guide <br> 
                            along the way and develop at your own pace <br>
                            that's comfortable.                            
                        </h3>
                        <h6> FANNIE MORENO</h6>
                        <p>/Founder & CEO</p>
                    </section>

                </div>
            </div>
        </div>
     </div>

     <!-- NUMERI STATISTICHE VERDI  -->

      <div class="text-dark">
        <div class="container">
            <div class="row">
                <div class="col-12 text-center">

                </div>
                     
                    <section class="stats">


                        <div class="col-3 text-center ">
                            <div class="stat-item">
                                <h2>1,926</h2>
                                <p>Finished Sessions</p>
                            </div>

                        </div>
                        <div class="col-3 text-center">
                            <div class="stat-item">
                                <h2>3,092+</h2>
                                <p>Enrolled Learners</p>
                            </div>

                        </div>
                        <div class="col-3 text-center">
                            <div class="stat-item">
                                <h2>200</h2>
                                <p>Online Instructors</p>
                            </div>

                        </div>
                        <div class="col-3 text-center">
                            <div class="stat-item">
                                <h2>100%</h2>
                                <p>Satisfaction Rate</p>
                            </div>

                        </div>
                    </section>

                </div>
            </div>
        </div>

        <!-- SEZIONE 2-B WHITE  -->

    
    <section class="hero text-dark">


        <button class="cta-button">Get Started For Free</button>
    </section>



    <section class="services">
        <h2>Services We Can Provide For My Clients.</h2>
        <div class="service-grid">
            <div class="service-item">
                <h3>Graphic Design</h3>
                <p>Have a passion for graphics and arts? Show your talents with confidence and self-assertiveness.</p>
            </div>
            <div class="service-item">
                <h3>Business Administration</h3>
                <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
            </div>
            <div class="service-item">
                <h3>Web Development</h3>
                <p>Learn to start building a web page from scratch. You decide your own pace, course and speed.</p>
            </div>
        </div>
    </section>

    <section class="courses">
        <h2>Latest Featured Courses</h2>
        <div class="course-grid">
            <!-- Course items would go here -->
        </div>
    </section>

    <section class="testimonial">
        <h2>Why People Talk About MaxCoach?</h2>
        <blockquote>
            "I can help to learn at my own pace, follow my own schedule and choose the subject I want to learn from the
            syllabus. Great study portal for people like me."
        </blockquote>
        <p>Mina Hollace</p>
    </section>

    <section class="blog">
        <h2>Latest on Our Blogs</h2>
        <div class="blog-grid">
            <!-- Blog post items would go here -->
        </div>
    </section>

</template>

<script>
export default {
    name: 'Main'
}
</script>

<style scoped>
/* ---------------PROVE */

 
        .side-image-1 {
            max-width: 400px;
            height: auto;
        }
        .image-wrapper {
            position: relative;
            height: 300px; /* Adjust this value based on your needs */
        }
        
        .right-image {
            position: absolute;
            bottom: -50px; /* Adjust this value to move the image lower */
            right: 0;
        }   
        .right-image {
            position: absolute;
            bottom: -150px; /* Adjust this value to move the image lower */
            right: 0;
        }
 







main {
    padding: 2rem;
}

.bg-blu1 {
    background-color: #1f1f52;
}

.hero {
    text-align: center;
    margin-bottom: 2rem;
}

.hero h1 {
    font-weight: 500;
}


.stats {
    display: flex;
    justify-content: space-around;
    margin-bottom: 2rem;
}

.services,
.courses,
.testimonial,
.blog {
    margin-bottom: 2rem;
}

.service-grid,
.course-grid,
.blog-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
}

.cta-button {
    background-color: #57c9f1;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    cursor: pointer;
}
</style>