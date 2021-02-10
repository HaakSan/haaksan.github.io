# haaksan.github.io

<!DOCTYPE html>
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
