<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>University</title>
  	<!-- ================== NAVBAR ================== -->
<header>
  <nav class="navbar">
  <!-- Logo -->
  <a href="Index.html" class="logo">
  <img src="logo1.PNG" alt="my logo" style=" height: 50px; margin-top: 10px; 
 border-radius: 80px;">
  <span class="university-name">SAMZY TECHH </span>
  </a>
     <!-- ================== NAVIGATION LINKS ================== -->

  <ul class="nav-links" id="navLinks">
    <li><a href="Index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="academics.html">Admission</a></li>
    <li><a href="acadeem.html">Academics</a></li>
    <li><a href="campuslife.html">Campus Life</a></li>
    <li><a href="form.html">Admission form</a></li>
    <li><a href="contactus.html" class="btn-apply">Apply Now</a></li>
    </ul>
  
   <!-- ================== Hamburger Menu for Mobile ================== -->

   <div class="hamburger" id="hamburger">
    <span></span>
    <span></span>
    <span></span>
  </div>
  <script>
    document.addEventListener("DOMContentLoaded", function () {
    
      const hamburger = document.getElementById("hamburger");
      const navLinks = document.getElementById("navLinks");
    
      hamburger.addEventListener("click", function () {
        navLinks.classList.toggle("active");
      });
    
    });
    </script>
</nav>
</header>
  <br>
  <br>
   <!-- ================== HERO SECTION ================== -->
   <script>
    const text = "Welcome To Samzy Techh University Website.";
    let index = 0;
    let speed = 80;
    
    function typeEffect() {
        if (index < text.length) {
            document.getElementById("typing").innerHTML += text.charAt(index);
            index++;
            setTimeout(typeEffect, speed);
        }
    }
    
    window.onload = typeEffect;
    </script>
<section class="hero">
  <div class="overlay"></div>
  
  <div class="hero-content">
      <h1 style="font-size: 50px;">
           <span id="typing"></span>
      </h1>
<p>Join Samzy Techh University and start your journey to greatness today.

</p>
  <div class="hero-buttons">
  <a href="contactus.html" class="btn-primary">Apply Now</a>
  <a href="acadeem.html" class="btn-secondary">Explore Programs</a>
  </div>
  </div>
  </div>
  </section>
      <!-- ================== ABOUT US ================== -->
<section class="about" id="about">
  <!-- Image: students in lecture hall -->
  <div class="about-container" style="max-width: 100%;">
  <div class="about-text">
  <h2>A Legacy of Excellence</h2>
  <p style="color: black;">At Samzy Techh University, we are committed to raising global<br> leaders who combine knowledge, character, and innovation to<br> solve the world’s challenges. foundation is built on excellence,<br> integrity, and impact, preparing students to transform societies.</p>
  </div>
  <div class="about-image">
  <img src="samzy5.png" alt="Students in lecture hall">
  </div>
  </div>
  </section>
       <!-- ================== BAKO ================== -->
       <div class="bako">
      <h2 style="color: green; font-size: 27px;  text-align: center; font-family: Arial, Helvetica, sans-serif;">World-Class Academic Faculties</h2>
      <p style="color: black; text-align: center;">From Cutting-edge Sciences To The Art, Buiness, And Engineering, Our Faculties Equip Student With Relevant
        Skills For the 21st Century
      </p>
             <!-- ================== FACULTIES ================== -->
      <section class="Faculties">
        <div class="faculty-container">
          <div class="faculty-card">
            <img src="oloko1.png" alt="">
            <div class="faculty-text">Faculty of engineering
            </div>
          </div>
          <div class="faculty-card">
            <img src="oloko2.png" alt="">
            <div class="faculty-text">Faculty of Business & Management</div>
          </div>
          <div class="faculty-card">
            <img src="samzy5.png" alt="">
            <div class="faculty-text">Faculty of Art & Social Science</div>
          </div>
          <div class="faculty-card">
            <img src="samzy11.png" alt="">
            <div class="faculty-text">Faculty of Law & Government</div>
          </div>
        </div>
        <button class="one" style="margin-top: 40px;  border-radius: 10px; color: white; height: 40px; width: 150px; text-decoration: none; background: yellow;">
          <a href="acadeem.html">Explore all program</a>
        </button>

      </section>
         <!-- ================== DEGREE ================== -->

      <section class="degree">
        <h2 style="text-align: center; color: green;"> Why Student Choose Samzy Techh University</h2>
        <br>
        <div class="degree-container">
          <div class="degree-card">
            <div class="degree-text"> Building Successfull Leader</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> Globally Recongnize Degree</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> International Exchange Oportunity</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> Innovation And Enterpreneurship Hub</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> State Of The Art Campus Facilities</div>
            
          </div>
        </div>
        
      </section>
      
      </div>
      
      <!-- ================== DEGREE ================== -->

      <section class="degree">
        <div class="degree-container">
          <div class="degree-card">
            <div class="degree-text"> Recognized for academic excellence</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> Learn From globally Experienced professor and mentor.</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> We Nuture Character, Cofidence And Leadership</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> We are Dedicated To Academic Excellence</div>
          </div>
          <div class="degree-card">
            <div class="degree-text"> Advance our student to sturdy with masters's and PhD Programs</div>
          </div>
        </div>
      </section>
      </div>
       <!-- Highlights -->
       <ul class="about-highlights">
        <li>🚀  Samzy Techh University Always Keep learning and improving</li>
        <li>🚀 Samzy Techh University is designed to spark innovation and collaboration.</li>
        <li>🚀 Samzy Techh University nurture critical thinker, innovators, and leaders equipped for global future.</li>
        <li>🚀 Samzy Techh University Explore program that combine academic exellence with real world oportunity.</li>
      </ul>
         <!-- ================== GLOBAL ================== -->
         <section class="global">
        <h2 style="color: black;">Experience Vibrant Campus Life</h2>
        <br>
        <div class="global-container" style="display: grid;">
          <div class="global-card">
            <img src="samzy8.png" alt="" width="100%">
            <div class="global-text">Sharing Knowledge To Each Other
            </div>
          </div>
          <div class="global-card">
            <img src="samzy10.png" alt="" style="width: 100%; gap: 10px;">
            <div class="global-text">Student Learning In Class</div>
          </div>
          <div class="global-card">
            <img src="samzy20.png" alt="" style="width: 100%; gap: 10px;">
            <div class="global-text">Celebrating the Achivers</div>
          </div>
          <div class="global-card">
            <img src="samzy21.png" alt="" width="100%">
            <div class="global-text">Listening To More Tips From The Advisor</div>
          </div>
        </div>
      </section> 
         <!-- ================== UPDATED ================== -->
         <section class="updated">
        <h2 style="color: green; text-align: center;">Stay Updated</h2>
        <br>
        <div class="updated-container" style="display: grid;">
          <div class="updated-card">
            <img src="samzy7.png" alt="" width="100%">
            <div class="updated-text" style="color: green; font-size: 15px;"><h3>Convocation Ceremoney 2026</h3>
              <p style="color: black;">Join Us In Celebrating Our Graduate With An Inspiring Ceremony</p>
            </div>
          </div>
          <div class="updated-card">
            <img src="oloko6.png" alt="" style="width: 100%; gap: 10px;">
            <div class="updated-text" style="color: green; font-size: medium;"><h3>Student Innovation Challenge</h3>
              <p style="color: black;"> Our Student Showcase Their Entrepreneurial And Teach Talent</p>
            </div>
          </div>
          <div class="updated-card">
            <img src="oloko3.png" alt="" width="100%">
            <div class="updated-text" style="color: green;"><h3>International Researcch Conference</h3>
              <p style="color: black;">Leading Scholars Gathering to Discuss Breakthrough And Innovations</p>
            </div>
          </div>
        </div>
      </section> 
         <!-- ================== IMPACT ================== -->
         <section class="impact">
        <h2 style="text-align: center; color:green"> Voice Of Impact</h2>
        <br>
        <div class="impact-container">
          <div class="impact-card">
            <div class="impact-text"> Samzy techh university Gave Me The Platform To Build My Global Career."" </div>
            <p style="color: green; font-style: bold; text-align: center; font-size: 17px;">- Williams Class Of 2024</p>
          </div>
          <div class="impact-card">
            <div class="impact-text"> The Teaching Quality And Facilities Are unmatched In Africa."</div>
            <p style="color: green; font-style: bold; text-align: center; font-size: 17px;">- Current Student</p>
          </div>
          <div class="impact-card">
            <div class="impact-text"> Partnershipt With industries Helped Me Lauch My Startup."</div>
            <p style="color: green; font-style: bold; text-align: center; font-size: 17px;">- Entrepreneur Graduate</p>
          </div>
          <div class="impact-card">
            <div class="impact-text"> Sturding In Samzy Techh University Make Me Acchive My Goals</div>
            <p style="color: green; font-style: bold; text-align: center; font-size: 17px;">- Aliana</p>
          </div>
        </div>
        
      </section>
      </div>
      
       	<!-- ================== CALL TO ACTION ================== -->
<section class="cta">
  <h2>Your Journey to Greatness Begins Here</h2>
  <a href="academics.html" class="btn-primary">Apply for Admission</a>
  </section>
       	<!-- ================== FOOTER ================== -->
         <footer class="footer">        
          <div class="footer-col"> 
              <a href="" style="color: yellow; font-size: 21px; font-family: Arial, Helvetica, sans-serif;">About Us</a>
              <p style="font-family: Arial, Helvetica, sans-serif; font-size: 17px;">Samzy Techh University Is Dedicated To
                <br> Academic Excellence , Leadership<br> Development Global Impact
              </p>
  
          </div>
          <div class="footer-col">
              <a href="" style="color: yellow; font-size: 21px; font-family: Arial, Helvetica, sans-serif;">Quick Links</a>
              <a href="about.html" style="font-family: Arial, Helvetica, sans-serif;"> About</a>
              <a href="acadeem.html" style="font-family: Arial, Helvetica, sans-serif;"> Academic</a>
              <a href="academics.html" style="font-family: Arial, Helvetica, sans-serif;">Admissions</a>
              <a href="campuslife.html" style="font-family: Arial, Helvetica, sans-serif;"> Campus Life</a>
          </div>
          <div class="footer-col"> 
            <a href="" style="color: yellow; font-size: 21px; font-family: Arial, Helvetica, sans-serif;">Contact Us</a>
            <p style="font-family: Arial, Helvetica, sans-serif;">Email: samueloloko002@gmail.com</p>
            <p style="font-family: Arial, Helvetica, sans-serif;">Phone: +234 916 069 8767  </p>
            <p style="font-family: Arial, Helvetica, sans-serif;">Address: Ondo Road Adebowale, Lagos Nigerian</p>
        </div>
        </footer>
      </footer>
      <hr>
      <footer class="nit">
        ©2026. Samzy Techh University . All Rights Reserved.

#css code
/* ================== RESET ================== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
    transition: all 0.3s ease-in-out;
  }
  html, body {
    width: 100%;
    min-height: 100%;
    color: #fff;
    line-height: 1.6;
    overflow-x: hidden;
  }
  /* ================== VARIABLES ================== */
  :root {
    --green: #0eaa80; /* deep emerald */
    --gold: #facc15; /* brighter gold */
    --white: #ffffff;
    --gray: #f5f5f5;
    --dark-gray: #333333;
  }
  
  /* ================== GLOBAL STYLES ================== */
  body {
    line-height: 1.6;
    color: var(--dark-gray);
  }
  
  a {
    text-decoration: none;
  }
  
  img {
    max-width: 100%;
    height: auto;
    display: block;
  }
  
  section {
    padding: 60px 20px;
  }
  
  /* ================== NAVBAR ================== */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
    background: var(--green);
    color: var(--white);
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1); 
  }
  .logo {
    display: flex;
    align-items: center;
    gap: 10px;
  }
  
  .logo img {
    height: 50px;
  }
  
  .university-name {
    color: var(--gold);
    font-size: 1.0rem;
    font-weight: bold;
    letter-spacing: 1px;
    font-family: Georgia, 'Times New Roman', Times, serif;
  }
  
  
  .nav-links {
    display: flex;
    list-style: none;
    gap: 20px;
  }
  
  .nav-links li a {
    color: var(--white);
    font-weight: 500;
    transition: color 0.1s;
  }
  
  .nav-links li a:hover {
    color: var(--gold);
  }
  
  .btn-apply {
    background: var(--gold);
    color: var(--green) !important;
    padding: 8px 15px;
    border-radius: 5px;
    font-weight: bold;
   }
   .btn-apply:hover{
    background: white;
   }
    /* ================== Hamburger Menu for Mobile ================== */

  .hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
    gap: 5px;
  }
  
  .hamburger span {
    width: 25px;
    height: 3px;
    background: var(--white);
    border-radius: 3px;
  }
  @media (max-width: 768px) {

    .nav-links {
      position: fixed;
      top: 80px;
      right: -100%;
      background: var(--green);
      flex-direction: column;
      width: 100%;
      text-align: center;
      padding: 20px 0;
      transition: right 0.3s ease-in-out;
    }
  
    .nav-links.active {
      right: 0;
    }
  
    .hamburger {
      display: flex;
    }
  }
  /* ================== HERO ================== */
.hero {
  height: 100vh;
  width: 100%;
  background: url("samzy1.png") no-repeat center center/cover;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  position: relative;
  overflow: hidden;
}
/* BLINKING CURSOR EFFECT */
#typing::after {
  content: "|";
  margin-left: 5px;
  animation: blink 5s infinite;
}

@keyframes blink {
  0% { opacity: 1; }
  50% { opacity: 0; }
  100% { opacity: 1; }
}
/* DARK OVERLAY */
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: green
      
  ;
}

.heroCanvas {
  position: absolute;
  top: 0;
  opacity: 5;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 2;
  pointer-events: none;
}

.hero-overlay {
  position: relative;
  z-index: 1;
  background-color:#0eaa80;
  backdrop-filter: blur(1px);
  width: 1000%;
  height: 1000%;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 5px;
}

.hero-content {
  position: relative;
  z-index: 3;
  text-align: center;
  color: #fff;
  max-width: 800px;
  padding: 0 20px;
}

.hero-content h1 {
  font-size: 2rem;
  font-weight: 700;
  color: var(--gold);
  text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
  margin-bottom: 20px;
  min-height: 60px; /* prevents layout shift during typewriter */
}

.hero-content p {
  font-size: 17px;
  margin-bottom: 20px;
  opacity: 0;
  animation: fadeInUp 1s ease 1s forwards;
}

.hero-buttons {
  display: flex;
  gap: 1rem;          /* space between buttons */
  justify-content: center; /* center them */
  flex-wrap: wrap;    /* allow them to move to new line if no space */
}

.hero-buttons a {
  padding: 12px 25px;
  margin: 0 10px;
  border-radius: 5px;
  font-weight: bold;
  transition: all 0.3s ease;
}

.btn-primary {
  background: var(--gold);
  color: var(--green);
}

.btn-primary:hover {
  background: #fff;
  color: var(--green);
}

.btn-secondary {
  background: transparent;
  border: 2px solid var(--gold);
  color: var(--gold);
}

.btn-secondary:hover {
  background: var(--gold);
  color: #fff;
}
/* Make typewriter text stand out */
.typewriters {
  border-right: 2px solid var(--gold);
  padding-right: 2px;
  white-space: normal;
  display: inline-block;
  transition: right 1.3s ease-in-out;
  color: #facc15;
  font-weight: bold;
  animation: blink 1.8s infinite;
}


/* Animation Keyframes */
@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(30px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}


/* ================== ABOUT ================== */
.about{
  padding: 10px;
}
.about-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  max-width: 100%;
  gap: 40px;
}

.about-text {
  padding: 10px;
  flex: 1;
  flex-wrap: wrap;
  align-items: flex-start;
  flex: 1 1 350px;
font-family: Arial, Helvetica, sans-serif;
  max-width: 1100px;
}


.about-text h2 {
  font-size: 2rem;
  width: 100%;
  min-width: 280px;
  color: var(--green);
  margin-bottom: 15px;
}

.about-text p {
  font-size: 1rem;
  margin-bottom: 20px;
  width: 100%;
}

.about-text .btn-primary {
  background: var(--gold);
  color: var(--green);
  padding: 10px 20px;
  border-radius: 5px;
}

.about-image {
  flex: 1;
  width: 100%;
}


/* ================== FACULTIES ================== */
.faculties{
    padding: 10px;
    flex-wrap: wrap;
  gap: 40px;
  align-items: center;
  padding: 10px 20px;
  display: flex;
  justify-content: space-between;
}
.faculties h2{
font-size: 28px;
    margin-bottom: 25px;
    color: green;
}
.faculty-card:hover{
    color: black;
}
.faculty-card{
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(1,1,1,1.1);
}
.faculty-text{
    padding: 15px;
    font-weight: bold;
    text-align: center;
}
.faculty-container{
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
}
.faculty-card img{
    width: 100%;
    height: 160px;
    object-fit: cover;
}
.prog{
    background: yellow;
    border-radius: 10px;
    height: 30px;
    margin-left: 10px;
    margin-top: 10px;
}
  /* ================== DEGREE ================== */

.degree{
    padding: 10px;
}
.degree-card{
    background: rgb(14, 207, 78);
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(1,1,1,1.1);
}
.degree-text{
    padding: 15px;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    text-align: center;
}
.degree-container{
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
}
.about-highlights {
  list-style: none;
  padding: 0;
  margin: 20px 0;
  color: white;
  background: gold;
}

.about-highlights li {
  margin: 10px 0;
  padding: 12px;
  font-size: 18px;
  border-radius: 8px;
  background: rgb(14, 207, 78);
  transition: 0.3s;
}
.about-highlights:hover{
  color: black;
  background: var(--dark-gray);
}
  /* ================== GLOBAL ================== */

.global{
    padding: 10px;
}
.global-container{
    display: grid;
    gap: 10px;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
}
.global-card img{
    width: 100%;
    height: 160px;
    object-fit: cover;
}
.global-card{
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(1,1,1,1.1);
}
.global-text{
    padding: 15px;
    font-weight: bold;
    text-align: center;
}
  /* ================== UPDATED ================== */

.updated{
    padding: 10px;
}
.updated-card{
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(2,2,2,2.2);
}
.updated-container{
    display: grid;
    gap: 10px;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
}
.updated-card img{
    width: 100%;
    height: 160px;
    object-fit: cover;
}
.updated-text{
    padding: 15px;
    font-weight: bold;
    text-align: center;
}
  /* ================== IMPACT ================== */

.impact{
    padding: 10px;
}
.impact-card{
    background: white;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(1,1,1,1.1);
}
.impact-text{
    padding: 15px;
    font-style: italic;
    font-weight: bold;
    text-align: center;
}
.impact-container{
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
}
.impact-text p{
    color: green;
}

/* ================== CALL TO ACTION ================== */
.cta {
  background: green;
  color: var(--white);
  text-align: center;
  padding: 60px 20px;
}

.cta h2 {
  font-size: 1.8rem;
  margin-bottom: 20px;
}

.cta .btn-primary {
  background: var(--gold);
  color: var(--green);
  padding: 12px 25px;
  border-radius: 5px;
}
/* ================== FOOTER ================== */
.next{
    background: green;
    height: 300px;
}
.nexts h2 {
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
}
.butt{
   margin-left: 550px; 
   margin-top: 30px;
   width: 160px;
   height: 40px;
   border-radius: 10px;
   margin-top: 70px;
   color: green;
   background: yellow;
   font-family: Arial, Helvetica, sans-serif;
}
/* ================== FOOTER ================== */

.footer{
  color: #fff;
  flex-wrap: wrap;
  gap: 40px;
  align-items: center;
  padding: 10px 20px;
  display: flex;
  background: green;
  justify-content: space-between;
}
.foot{
  display: flex;
  justify-content: space-around;
  padding: 30px 10px;
  flex-wrap: wrap;
  font-size: 14px;
  background: green;
}
.foot p{
  color: yellow;
  display: flex;

}
.foots{
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  font-size: 14px;
  padding: 10px;
  background: green;
}
.foots p{
  color: rgb(248, 248, 244);
  display: flex;
}

.footer a{
  display: block;
  color: #fff;
  text-decoration: none;
  margin-bottom: 10px;
}
.nit{
  text-align: center;
  background: green;
  color: white;
  padding: 20px;
}




        
      </footer>
</body>
</html>
