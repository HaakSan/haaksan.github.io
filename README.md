# haaksan.github.io

<!DOCTYPE html>
html{
  scroll-behavior: smooth;
}  
body {
  background-image: linear-gradient(#c4c1d9, #2e7794, #44b857, #23fada);
  background-color: grey;
  font-family: verdana, copperplate, tahoma;
  line-height: 2;
  text-align: center;
  margin: 0;
  text-align: center;
  justify-content: center;
}
h2{
  font-size: 25px;
  color: white;
  text-shadow: 2px 2px black;
}  
a:focus {
  outline: 3px dashed crimson;
}

/* Navigation bar CSS starts here */

#navbar{
  position: fixed;
  width: 100%;
  top: 0;
  text-align: center;
  font-weight: bold;
  text-shadow: 2px 2px pink;
  z-index: 1;
  transition: background 0.3s ease-in-out;
}    
#navbar a {
  float: right;
  color: black;
  padding: 15px;
  text-decoration: none;
  font-size: 20px;   
  transition: background-color 2000ms ease-in-out, border-radius 2000ms ease-in-out;
}
#navbar a:hover {
  background-color: lightgrey;
  border-radius: 200px;
}

/* Removing navbar for phones. Find out how to make it dropdown instead*/

@media (max-width:600px) {
#navbar {
  display: none;
}
}

/* Welcome section CSS starts here */

#welcome-section{
  min-height: 100vh;
  height: auto;
  margin: 0;
  justify-content: center;
  text-align: center;
}
#header{
  font-size: 40px;
  position: absolute;
  text-shadow: 2px 2px pink;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

/* Projects section CSS starts here */

#projects{
  height: auto;
  min-height: vmax;
  height: auto;
  min-width: vmax;
  width: auto;
  margin: 0;
  padding-bottom: 50px;
}
#container{
  width: 80%;
  margin: 0 auto;
  padding-top: 50px;
  font-size: 20px;
  font-weight: bold;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  grid-gap: 50px 100px;
  color: black;
  text-shadow: 2px 2px white;
}
@media (max-width:600px) {
#container {
  grid-template-columns: 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr;
}
}
.project-tile{
  background-color: #ffb3fc;
  box-shadow: 10px 5px 25px black;
  border-radius: 2px;
  display: block;
  padding-bottom: 5px;
  transition: transform 1500ms ease-in-out;
}
.project-tile:hover{
  transform: scale(1.1);
}
.tile-image{
  max-height: 200px;
  height: auto;
  max-width: 200px;
  width: auto;
  box-shadow: 10px 5px 25px black;
  border-color: black;
  border-width: 2px;
  border-style: solid;
}
.button{
  width: 60%;
  margin: 0 auto;
  padding: 5px;
  border-radius: 15px;
  border: none;
  background: linear-gradient(90deg, blue, #4287f5,   #4287f5, #4287f5, blue);
  box-shadow: 5px 5px 15px black;
  color: white;
  font-size: 15px;
  text-shadow: 1px 1px black;
  text-decoration: none;
  
}
#button_1:hover,
#button_2:hover,
#button_3:hover,
#button_4:hover {
  transform: scale(1.1);
  transition-duration: 1000ms;
  text-decoration: none;
}

/* Contact section CSS starts here */

#contact{
  color: black;
  min-height: 100vh;
  height: auto;
  margin: 0;
}  
.profile-links{
  color: black;
  text-decoration: none;
  text-shadow: 2px 2px pink; 
}
.profile-links:hover {
  font-size: 150%;
  transition-duration: 1000ms
}
#contact_form {
  width: 50%;
  background-color: #ffb3fc;
  box-shadow: 10px 5px 25px black;
  border-radius: 2px;
  margin: 0 auto;
  overflow: hidden;
  display: block;
  padding: 20px;
}
.input-box{
  background: transparent;
  border-color: grey;
  border-color: black;
  width: 90%;
  border:2px solid black;
  margin:0 auto;
  padding: 15px 5px;
  box-sizing:border-box;
  text-align: left;
}
.label{
  float: left;
  padding-left: 5%;
}
.input-box:hover{
  background-color: white;
  transition-duration: 1500ms;
}
#submit_button {
  font-weight: bold;
  font-size: 120%;
  text-align: right;
  margin-top: 30px;
}
#submit_button:hover{
  font-size: 150%;
}
::placeholder {
  color: grey;
  font-family: verdana;
}

/* Footer CSS starts here */

#footer {
  color: black;
  padding-top: 50px;
}
#fcc_logo {
  max-height: 5%;
  height: auto;
  max-width: 5%;
  width: auto;
}

<html lang="en">
  <head>
  <title>Sander Haak Portfolio Page</title>
</head>
  <body>
  
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
  
  <!-- I've tried my best to make this work my own. I've used information from FCC's curriculum and forum, W3Schools and other open forums and guides to make my own pages. If there has been any sort of infringement, feel free to contact me and I'll try and fix it. Contact info: shaak@live.nl -->
  
<section id="welcome-section">
    <header id="header">
    <h1> Hi, I'm Sander </h1>
    <h2>I'm a self-taught developer. Check my creations below!</h2>
    </header>
</section>
  
<nav id="navbar" class="navbar">
    <a href= "#contact" class="nav-link">Contact</a>
    <a href= "#projects" class="nav-link">Projects</a>
    <a href= "#welcome-section" class="nav-link">About</a>
</nav>
  
<!-- Projects section starts here --> 
  
 <main id="main">
    <section id="projects">
    <h2>Here are several projects I've made. Take a look!</h2>
      
        
      <div id="container">
        <div id="tribute_page" class="project-tile"><h3>Tribute page</h3>
      <img id="preview_1" class="tile-image" src="https://image.thum.io/get/maxAge/12/width/700/https://codepen.io/haaksan/full/qBaeggO" alt="FCC Logo">
      <div id="button_1"><a href="https://codepen.io/haaksan/pen/qBaeggO" class="button" target="_blank">Open page</a></div>
      </div>
        
        <div id="survey_page" class="project-tile"><h3>Survey page</h3><img id="preview_2" class="tile-image" src="https://image.thum.io/get/maxAge/12/width/700/https://codepen.io/haaksan/full/LYbPemB" alt="FCC Logo">
      <div id="button_2"><a href="https://codepen.io/haaksan/pen/LYbPemB" class="button" target="_blank">Open page</a></div>
      </div>
        
        <div id="product_page" class="project-tile"><h3>Product landing page</h3><img id="preview_3" class="tile-image" src="https://image.thum.io/get/maxAge/12/width/700/https://codepen.io/haaksan/full/WNobPRQ" alt="FCC Logo">
      <div id="button_3"><a href="https://codepen.io/haaksan/pen/WNobPRQ" class="button" target="_blank">Open page</a></div>
      </div>
        
        <div id="technical_page" class="project-tile"><h3>Technical product page</h3><img id="preview_4" class="tile-image" src="https://image.thum.io/get/maxAge/12/width/700/https://codepen.io/haaksan/full/xxRwRNj" alt="FCC Logo">
      <div id="button_4"><a href="https://codepen.io/haaksan/pen/xxRwRNj" class="button" target="_blank">Open page</a></div>
      </div> 
      </div>
  </section>
</main>
  
 <!-- Contact section starts here --> 
    
<section id="contact">
  <div id="profile_links">
       <h2> Interested? Let's get in touch!</h2><p><a id="profile-link" class= "profile-links" href="https://github.com/HaakSan" target="_blank">My <strong>GitHub</strong> profile</a></p>  
  <p><a class="profile-links" href="https://www.freecodecamp.org/fcc3fd9cd43-9d35-4e87-9c49-142f675539d4" target="_blank">My <strong>freeCodeCamp</strong> profile</a></p>
    
  </div>
  <div id="contact_form">
    <h2> You can also send me a message! </h2>
    <label id="name-label" for="name_input" class="label"> Name: </label>
      <input id="name_input" class="input-box" type="text" placeholder="Write your name here" required>
            
    <label id="email-label" for="email_input" class="label"> Email: </label>
      <input id="email_input" class="input-box" type="text" placeholder="Write your email here" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$" required>
        
    <label id="message-label" for="message_input" class="label"> Message: </label>
      <input id="message_input" class="input-box" type="text" placeholder="Write your message here" required >
        
       
    <label id="submit-label" for="submit_button"></label>
      <input id="submit_button" class="input-box" type="submit" value="Send message!">
</div>
</section>
      
<!-- Footer starts here --> 
        
<footer id="footer">
  <p>This page is created by <a id="tribute-link" href="https://github.com/HaakSan" target="_blank">HaakSan</a> for <a id="fcc-link" href="https://www.freecodecamp.org/" target="_blank">freeCodeCamp</a> - 2021</p>
<img id="fcc_logo" src="https://th.bing.com/th/id/Rae91b723cbdab27450b707509964eb4d?rik=tAB%2bW1OErzuhZw&riu=http%3a%2f%2fstatic.libsyn.com%2fp%2fassets%2f2%2ff%2ff%2f7%2f2ff7cc8aa33fe438%2ffreecodecamp-square-logo-large-1400.jpg&ehk=%2fUOMfC%2fOXpTE%2b6d8IQIVtoT4gWo0%2bPO7J%2bWlbKZSt%2bE%3d&risl=&pid=ImgRaw" alt="FCC Logo">
</footer>
  </body>
</html>
