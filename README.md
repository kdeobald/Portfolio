<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coding & Marketing Portfolio</title>
    <link rel="stylesheet" href="styles.css">
 <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200;300&display=swap" rel="stylesheet">

  </head>
  <navbar id="navbar">
    <ul id="nav-buttons">
        <li>
          <a class="nav-link" href="#about">About</a></li>
          <li>
          <a class="nav-link" href="#work">Work</a>
        </li>
      </ul>
  </navbar>
  <body>
    <section id="welcome-section">
      <h1>Welcome to my portfolio!<br></h1>
      <h2>All my coding and marketing projects live here.</h2>
      <p id="About">Each of the projects below were completed with pure HTML & CSS according to specific parameters for my FreeCodeCamp course. I am currently studying Javascript, so more varied content will be coming soon. My certifications will be listed below as they are completed.</p>
     <div class="button">
        <a href="https://www.freecodecamp.org/certification/kdeobald/responsive-web-design" target="_blank" class="profile-link" >Responsive Website Design - Free Code Camp - March 2023</a>
      </div>
<div class='button'>
<a href='https://app.hubspot.com/academy/achievements/5ktznpfx/en/1/katie-deobald/inbound'  target="_blank" class="profile-link" >Inbound Certified - Hubspot Academy 2023</a>
</div>
<div class='button'>
<a href='https://app.hubspot.com/academy/achievements/kdmsgp86/en/1/katie-deobald/hubspot-marketing-software' target="_blank" class="profile-link" >Marketing Software Certified - Hubspot Academy 2023</a>
</div>
    </section>

    <section id="projects">
      <div class="project-tile" id="petshop">
        <a href="https://kdeobald.github.io/petshop/index.html">
          <h3 id="Work" class="project-title">Store Landing Page</h3>
          <img src="https://res.cloudinary.com/dawl1cmui/image/upload/v1678930031/Screenshots%20For%20Portfolio/Thumbnail_0000_ProductLandingPageScreenshot_rclujd.jpg">
        </a>
        <p class="project-p">For this project, the course goal was a landing page but this did not fit with my learning goals at the time so I did a parody store landing page instead. I wrote all the copy and did all the UI design in Figma, then recreated it within the limitations of what I could achieve without any Javascript in the Free Code Camp editor.</p>
      </div>

      <div class="project-tile" id="kirk">
        <a href="https://kdeobald.github.io/tributepage/">
          <h3 class="project-title">Tribute Page</h3>
          <img src="https://res.cloudinary.com/dawl1cmui/image/upload/v1678930030/Screenshots%20For%20Portfolio/Thumbnail_0003_kirk1_r28zun.jpg">
        </a>
        <p class="project-p">I am a huge nerd, so for this project I wanted to make a wiki entry about Kirk, but done with the UI style used on all the touch screens from Star Trek: The Next Generation.</p>
      </div>

      <div class="project-tile" id="techdoc">
        <a href="https://kdeobald.github.io/techdoc/">
          <h3 class="project-title">Technical Documentation Page</h3>
          <img src="https://res.cloudinary.com/dawl1cmui/image/upload/v1678930033/Screenshots%20For%20Portfolio/Thumbnail_0001_technicaldocscreenshot_ebg7xu.jpg">
        </a>
        <p class="project-p">Given the volume of data I wanted to put in just for the practice, I stuck pretty close to requirements for this one as well. All text content was copied from the course example, but the code is my own.</p>
      </div>

      <div class="project-tile" id="techdoc">
        <a href="https://kdeobald.github.io/survey/">
          <h3 class="project-title">Survey Form</h3>
          <img src="https://res.cloudinary.com/dawl1cmui/image/upload/v1678930031/Screenshots%20For%20Portfolio/Thumbnail_0002_FormScreenshot_dwrxos.jpg">
       </a>
        <p class="project-p">As this was one of my earlier assignments, I stuck pretty close to the requirements.</p>
      </div>
    </section>
  </body>
</html>
