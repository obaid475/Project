<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      *{
    margin: 0%;
    box-sizing: border-box;
}

.firstline-1{
    justify-content: space-between;
    display: flex;
    background-color: gray;
    padding: 10px 0px 10px 0px;

}
.firstline-1 h2 a{
    color: black;
    text-decoration: none;
    margin-left: 40px;
}
.firstline-1 ul{
    display: flex;
    list-style-type: none;
    margin-right: 40px;

}
.firstline-1 ul li{
    margin-left: 40px;
}
.secondline-1{
    background-color: rgba(11, 4, 2, 0.336);
    color: white;
    padding: 10px 0px 10px 0px;
    
}
.secondline-1 h1{
    text-align: center;
}
.thirdline-1{
    background-color: white;
    padding: 10px 0px 10px 0px;

}
.thirdline-1 ul{
    display: flex;
    list-style-type: none;
    text-align: center;
}
.thirdline-1 ul li{
    margin-left: 20px;

}
.thirdline-1 ul li a{
    color: black;
    text-decoration: none;
}
.slideshow-container {
    max-width: 1000px;
    position: relative;
    margin: auto;
  }
  
  /* Hide the images by default */
  .mySlides {
    display: none;
  }
  
  /* Next & previous buttons */
  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    margin-top: -22px;
    padding: 16px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
    user-select: none;
  }
  
  /* Position the "next button" to the right */
  .next {
    right: 0;
    border-radius: 3px 0 0 3px;
  }
  
  /* On hover, add a black background color with a little bit see-through */
  .prev:hover, .next:hover {
    background-color: rgba(0,0,0,0.8);
  }
  
  /* Caption text */
  .text {
    color: #f2f2f2;
    font-size: 15px;
    padding: 8px 12px;
    position: absolute;
    bottom: 8px;
    width: 100%;
    text-align: center;
  }
  
  /* Number text (1/3 etc) */
  .numbertext {
    color: #f2f2f2;
    font-size: 12px;
    padding: 8px 12px;
    position: absolute;
    top: 0;
  }
  
  /* The dots/bullets/indicators */
  .dot {
    cursor: pointer;
    height: 15px;
    width: 15px;
    margin: 0 2px;
    background-color: #bbb;
    border-radius: 50%;
    display: inline-block;
    transition: background-color 0.6s ease;
  }
  
  .active, .dot:hover {
    background-color: #717171;
  }
  
  /* Fading animation */
  .fade {
    animation-name: fade;
    animation-duration: 1.5s;
  }
  
  @keyframes fade {
    from {opacity: .4}
    to {opacity: 1}
  }
.fourthline-1{
    width: 100%;
    display: flex;
}
.fourthline-2{
    width: 30%;
    margin: 0% 5% 0% 15%;
    
    
    
   
}
.fourthline-3{
    width: 40%;
}
.forback-1{
    background-color: white;
    box-shadow: 0px 0px 10px black;
    width: 35%;
    height: 40vh;
    margin: 0% 5% 0% 5%;
    float: left;
    padding: 10px;
    margin-top: 20px;
    border-radius: 20px;
    
    
    
}
 .forback-1 .img-1{
    background-size: cover;
    width: 130px;
    border-radius: 20px 20px 0px 0px;
    border: 2px solid rgb(0, 0, 171);
}
.forback-1 h3{
  color: rgb(83, 83, 255);
  padding: 10px 5px 0px 0px;
  text-align: center;
}
.forback-1 h4{
  text-align: center;
}

.fourthline-2 h2{
  text-align: left;
  margin-bottom: 10px;
  font-size: 18px;

}
.fourthline-2 p{
  text-align: justify;
}
.fourthline-2 a {
  text-decoration: none;
  position: relative;
  top: 50px;
  color: rgb(68, 68, 255);

}
.fourthline-2 a:hover{
  color: black;
  text-decoration: underline;
  transition: 0.3s;

}
.fourthline3-1{
  width: 500px;
  margin-top: 20px;
  padding: 10px;
  height: 60vh;
  overflow-y: scroll;
}
.fourthline3-1 p{
  color: gray;
  margin: 20px ;
  border-bottom: 1px solid gray;
  
  
}
.fourthline3-1 a{
  padding: 30px;
  position: relative;
  bottom: 20px;
  text-decoration: none;
  letter-spacing: 1px;
  text-align: justify;
  }
  .fithline1 {
    width: 100%;
    margin-top: 100px;

  }
  .fifthline1-1{
    margin-left: 500px;
    width: 500px;
    background-color: blue;
    border-radius: 10px;
    color: white;
    padding: 10px;
    box-shadow: 0px 0px 20px black;

  }
  .fifthline1-1 h1{
    text-align: center;
  }
  .fifthline1-1  button{
    width: 400px;
    margin-left: 45px;
    margin-top: 30px;
    padding: 10px;
    color: rgb(0, 0, 0);
    cursor: pointer;
    
  }
  .fifthline1-1  button:hover{
    background-color: black;
    transition: 0.2s;
    background-color: white;
  }
   .seventhline1{
    width: 100%;
    margin-top: 50px;
    
   }
  .seventhlin1-1{
    width: 60%;
    margin: 0% 20% 0% 20%;
  }
  .seventhlin1-1 p{
    color: gray;
    margin-top: 10px;
    font-size: 20px;
  }
  .box1{
    width: 100%;
    
    padding: 10px;
    margin-top: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 5px;
    height: 25vh;
    margin-bottom: 30px;
    
    
  }
  .box1:hover{
    box-shadow: 0px 0px 10px black;
    transition: 0.3s;
  }
  .backimages{
    background-image: k;
    margin-top: 20px;
    float: left;
    width: 200px;
    height: 100px;
    font-size: 22px;
  }
  .con1 a{
    color: black;
    font-size: 20px;
    position: relative;
    top: 10px;
    text-decoration: none;
    bottom: 10px;
    
  }
  .con1 a:hover{
    color: rgb(46, 46, 201);
  }
  .con1 button{
    background-color: rgb(53, 72, 170);
    color: black;
    width: 150px;
    margin-top: 30px;
    padding:10px;
    border: none;
    border-radius: 10px;
    color: white;
  }
  .con1 button:hover{
    background-color: black;
    color: white;
    transition: 0.3s;

  }

  .eightline1{
    background-color: black;
    color: white;
    padding: 40px 0px 40px 0px;
    
  }
  .eightline1-1{
    width: 60%;
    display: flex;
    margin: 0% 20% 0% 20%;
    justify-content: space-between;
    padding: 40px 0px 40px 0px;
    border-bottom: 0.5px solid gray;
  }
  .eightline1-1 ul{
    list-style-type: none;
    margin-top: 30px;
    font-size: 20px;
    font-weight: 700;
  }
  .eightline1-1 ul li{
    font-size: 17px;
    margin-top: 20px;
  }
  .eightline1-1 ul li a{
    color: gray;
    text-decoration: none;
  }
  .eightline1-1 ul li a:hover{
    color: white;
    transition: 0.2s;
  }

 
  td{
    padding: 10px;
  }
  .table1{
    margin-top: 100px;
  }
  .lunch{
    rotate: 90deg;
    font-size: 20px;
    display: flex;
  }
 


    </style>
    
</head>
<body>
    <div class="firstline-1">
        <h2><a href="#">Integral University</a></h2>
        <ul class="list-1">
            <li><a href="#">+919335177775</a></li>
            <li><a href="#">info@iul.ac.in</a></li>
        </ul>
    </div>
    <div class=" secondline-1">
        <h1>Department of Computer Application</h1>
    </div>
    <div class="thirdline-1">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">PROGRAME</a></li>
            <li><a href="#">STUDENT</a></li>
            <li><a href="#">RESEARCH</a></li>
            <li><a href="#">ACTIVITIES</a></li>
            <li><a href="#">ACHIEVEMENTS</a></li>
            <li><a href="#">INFRASTRUCTURE</a></li>

        </ul>
    </div>
    <div class="slideshow-container">

        <!-- Full-width images with number and caption text -->
        <div class="mySlides fade">
          <div class="numbertext">1 / 3</div>
          <img src="https://blogger.googleusercontent.com/img/a/AVvXsEjepFkrbxot-c_oafa6eyk8SzoweiiH4ebBECB-8LjzW7GQ4GmhnEKFHydEjDl3hTk6clo-h9ckPk2rcWc9sh2qowt20_ZL_b8WxQwC8fJKB2GGCqCuGKs0r6dFSZ6soawRrWoJQBgkUnFLLCt03xwaqLIFOJdTu6EVJvx55ciEYIqg958dT3XMAoUQZg=s16000" style="width:100%">
          <div class="text">Caption Text</div>
        </div>
      
        <div class="mySlides fade">
          <div class="numbertext">2 / 3</div>
          <img src="https://blogger.googleusercontent.com/img/a/AVvXsEivlpjDMo_UyRBaI1TDxa6qhCvJIrkEdYL279ysuqRNw3j6nFapOow_0S4d5m10YcdMRryeE5mFjjthIAtu3uO-yny3cMKZNOrAroPFRHMtlbvuOPaoU6DPHsMXVXLPqOo45713n4_n-Awdr6Uv1tW8q2cPRTeK2J7bmb54af4IwfxoAO_O3bD5O2SKkw=s16000" style="width:100%">
          <div class="text">Caption Two</div>
        </div>
      
        <div class="mySlides fade">
          <div class="numbertext">3 / 3</div>
          <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiu-ENEb_N_WS07t6e9kcPjGNGaco5Z1wBwLAjVU21xWg2ToT9qZgQkQ3lxk6wyoXmYiXpuCvCK_x9DhIhA8xsQqJPf1Vqet66ATnW7LikodEfOkXA_Q46BekM8wRPW5eou3FxU-ao_gaurayk1_x0IdnOwe_GEfrKAscfgSWGbcQFn53T6ynydR2PLow/s16000/Academic%20Block-II.jpg" style="width:100%">
          <div class="text">Caption Three</div>
        </div>
      
        <!-- Next and previous buttons -->
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
      </div>
      <br>
      
      <!-- The dots/circles -->
      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
      </div>
      <div class="fourthline-1">
        <div class="fourthline-2">
            
            <div class="forback-1">
                <img class="img-1" src="Computer Application-Whats.jpeg" alt="">
                <h3>Dr.Mohammad Faisal</h3>
                
                <h4>(HOD)</h4>
            </div>
            <h2>
              Welcome to the Department of Computer Application of Integral University.
            </h2>
            <p>The Department was established in 2003 and is one of the most reputed academic departments in the field of Computer Application. The curriculum of this department is addressed to the students who wish to be distinguished as Software Developer, Computer System Analyst, Software Engineer, Software Application Architect, Hardware Engineer, Software Consultant, Database Administrator in the private and public sector. You can become part of this highly competitive and futuristic environment by enrolling for one of our exciting programs. The Department offers a 4 semester Bachelor program in Computer Application (BCA), 4 semester Master program in Computer Application,The combination of a dynamic and innovative curriculum that takes advantage of the latest technologies, with the experienced faculties of the Department, creates a fertile ground for the effective dissemination of knowledge and the development of the necessary skills for future professional recognition of the Department's students.</p>
            <a href="#">Learn more-></a>
        </div>
        <div class="fourthline-3">
            <h2>News & Annoucement</h2>
            <div class="fourthline3-1">
              <p>14/10/2022</p>
              <a href="#">September Issue of TechDose</a>

              <p>14/10/2022</p>
              <a href="#"> August Issue of TechDose</a>

              <p>15/08/2022</p>
              <a href="#">   July Issue of TechDose</a>

              <p>15/08/2022</p>
              <a href="#"> E-Souvenir_International E-Symposium_RAICT 2020_Organized by Department of Computer Application
              </a>
              
              <p>29/07/2022</p>
              <a href="#">June Issue of TechDose</a>
              <p>21/06/2022</p>
              <a href="#">May Issue TechDose</a>


            </div>
        </div>
      </div>

      <div class="fithline1">
        <div class="fifthline1-1">

          <h1> REGISTER YOUR INTEREST </h1>
          <button> GET IN TOUCH NOW </button>
         


        </div>
      </div>
      

      <div class=" table1">
        <center><h1>BCA 3rd year</h1></center>
        <center><h1>Program-Wise Time-Table </h1></center>
        <table border="1px">
          <tr>
            <th>Day/Period</th>

            <th><center><h1>1</h1></center>
            9:00AM - 9:50AM</th>

            <th><center><h1>2</h1></center>
              9:50AM - 10:40AM</th>

              <th><center><h1>3</h1></center>
                10:40AM - 11:30AM</th>

                <th><center><h1>4</h1></center>
                11:30AM - 12:20PM</th>


               <th><center><h1>Lunch Break</h1></center>
                12:20PM - 1:30PM</th>

                <th><center><h1>5</h1></center>
                  1:30PM - 2:30PM</th>

                  <th><center><h1>6</h1></center>
                    2:20PM - 3:10PM</th>

                    <th><center><h1>7</h1></center>
                      3:10PM - 4:00PM</th>



          </tr>

          <tr>
            <td>Monday</td>
            <td>CA301</td>
            <td>CA302</td>
            <td>CA304</td>
            <td>CA307</td>
            <td rowspan="7"><h1 class="lunch">Lunch Breakdown</h1></td>

            <td>CA311 LAB</td>
            <td>CA311 LAB</td>
            <td>CA311 LAB</td>
          </tr>


          <tr>
            <td>Tuesday</td>
            <td>CA307</td>
            <td>CA310 LAb</td>
            <td>CA310 LAB</td>
            <td>CA310 LAB</td>
            <td> &nbsp;  </td>
            <td>CA304</td>
            <td>CA301</td>
          </tr>


          <tr>
            <td>Wednesday</td>
            <td>CA303 </td>
            <td>CA303 </td>
            <td>&nbsp; </td>
            <td>&nbsp; </td>
            <td>&nbsp; </td>
            <td>CA302</td>
            <td>CA304</td>
          </tr>
          <tr>
            <td>Thursday</td>
            <td>CA307</td>
            <td>CA304</td>
            <td>CA302</td>
            <td>CA310</td>
            <td>CA301</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
          </tr>

          <tr>
            <td>Friday</td>
            <td>CA310 LAB</td>
            <td>CA310 LAB</td>
            <td>CA310 LAB</td>
            <td>CA304</td>
            <td>&nbsp;</td>
            <td>CA312 LAB</td>
            <td>CA312 LAB</td>
          </tr>

          <tr>
            <td>Saturday</td>
            <td>CA303</td>
            <td>CA302</td>
            <td>CA301</td>
            <td>CA307</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            
          </tr>
        </table>

      </div>

      <div class="seventhline1">
        <div class="seventhlin1-1">
          <h1>INTEGRAL EVENTS</h1>
          <p>Upcoming.Interest.Engaging </p>

          <div class="box1">
            <div class="backimages">
              1/11/2022
            </div>

            <div class="con1">
              <p> 01/11/2022 - 01/11/2022
              </p>
              <a href="#">Centre for Incubation & Entrepreneurship Development (CIED)</a>
              <br>
              <button>Learn more</button>

            </div>

          </div>
          
        </div>
        
        <div class="seventhlin1-1">
          

          <div class="box1">
            <div class="backimages">
              24/11/2022
            </div>

            <div class="con1">
              <p> 01/11/2022 - 01/11/2022
              </p>
              <a href="#">INDO-UZBEK MEET & INTERNATIONAL CONFERENCE
              </a>
              <br>
              <button>Learn more</button>

            </div>

          </div>
          
        </div>
        

      </div>
      <div class="eightline1">
        <div class="eightline1-1">
          <ul>
            Contact Us
            <li><a href="#"> 0522- 2890730, 2890812</a></li>
            <li><a href="#"> info@iul.ac.in </a></li>
            
          </ul>
          <ul>
            About us
            <li><a href="#">Overview
            </a></li>

            <li><a href="#">
           Vision & Mission</a>
            </li>
            
            
          </ul>

          
          <ul>
            Useful Links
            <li><a href="#">FAQs</a></li>
            <li><a href="#">Help Desk</a></li>
          </ul>
          <ul>Follow Us
            <li><a href="#">facebook</a></li>
            <li><a href="#">google+</a></li>
            <li><a href="#">twitter</a></li>
          </ul>

        </div>

      </div>

      <script type="text/javascript">
        let slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}
      </script>
</body>
</html>
