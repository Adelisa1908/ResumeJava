# ResumeJava
<!DOCTYPE html>
<html>

<head>
 
  <title>Adelisa Sirćo</title>
  <link href="style.css" rel="stylesheet" type ="text/css">
  <link href="reset.css" rel="stylesheet" type ="text/css">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href "https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&display=swap" rel="stylesheet">
   
</head>
  
<body >
 <nav class="nav_closed">
<a href="#mainnav" id="menu">MENU</a>
<ul id="navlist">
    <li><a href="#page-header">Home</a></li>
    <li><a href="#profile">Profile</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#contact">Contact</a></li>
</ul>

    
 </nav>
 
 <section id="page-header">
    
 
  <header>
  <h1>Adelisa Sirćo</h1>
  <h2>Electrical engineer</h2>
  </header>
  
 </section>
 <section id="profile"class="page-content">
  <div>
   <header>
    <h1>Profile</h1>
    <h2>Basic info</h2>
   </header>
   <article>
    <p>My name is Adelisa Sirćo. I was born 19.08.1998 in Sarajevo. My hometown is Olovo. Currently I live in Sarajevo. </p>
   </article>
  </div>
  
 </section>
 </section>
 <section id="skills"class="page-content">
  <div>
   <header>
    <h1>Skills</h1>
    <h2></h2>
   </header>
   <article>
    <li><img src="images/A.svg"alt="Skills"</li>
   </article>
  </div>
  
 </section>
 </section>
 <section id="education"class="page-content">
  <div>
   <header>
    <h1>Education</h1>
    <h2> </h2>
   </header>
   <article>
    <p>  OŠ "Avdo Smailović" 2004-2013<br>
    Gazi Husrev-begova medresa 2013-2017<br>
    International University of Sarajevo 2017-2021 </p>
   </article>
  </div>
  
 </section>
 </section>
 <section id="experience"class="page-content">
  <div>
   <header>
    <h1>Work experience</h1>
    <h2> </h2>
   </header>
   <article>
    <p>2012-2020 volounteer in "Fondacija Hastor" </p>
   </article>
  </div>
  
 </section>
 </section>
 <section id="contact"class="page-content">
  <div>
   <header>
    <h1>Contact</h1>
    <h2>sirco.sircoade@gmail.com</h2>
   </header>
   <article>
   
    <ul>
     
     <li>
      <a href="#" target="_blank"title="Facebook">Facebook</a>
     </li>
     <li>
      <a href="#" target="_blank"title="Instagram">Instagram</a>
     </li>
     <li>
      <a href="#" target="_blank"title="Linkedln">Linkedln</a>
     </li>
    </ul>
   </article>
  </div>
  
 </section>
  
  
  
  
 
  
  
<script src="js/jquery-3.5.1.min.js"type="text/javascript"></script>
<script type="text/javascript">
$(document).ready(function(){
$("#menu").click(function(){
$("nav.nav_closed").toggleClass("nav_open");
});
$("nav ul li a").click(function(){
 $("nav.nav_open").removeClass("nav_open");
});
});
</script>
<noscript>
 <ul id="mainnav">
    <li><a href="#page-header">Home</a></li>
    <li><a href="#profile">Profile</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#contact">Contact</a></li>
</ul>
</noscript>
</body>

</html>
