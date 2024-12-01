---
title: "Home"
layout: default
---

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

<style>
/* Hide the footer */
.site-footer {
    display: none;
}

.site-header {
    display: none;
}
</style>

<div class="container">
    <div class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom">
        <!-- Navigation Links -->
        <ul class="nav nav-pills">
            <li class="nav-item"><a href="index.html" class="nav-link active" aria-current="page">About</a></li>
            <li class="nav-item"><a href="research.html" class="nav-link" aria-current="page">Research</a></li>
            <li class="nav-item"><a href="publication.html" class="nav-link">Publications</a></li>
            <li class="nav-item"><a href="contact.html" class="nav-link">Contact</a></li>
        </ul>
    </div>
</div>

<style>
    /* Outer container to hold both the profile and content */
    .container {
        display: flex;
        justify-content: center;
        align-items: flex-start;
        margin-top: 30px;
        padding: 20px;
    }
    
    /* Profile box styles */
    .profile-box {
        border: 2px solid #ddd;
        border-radius: 12px;
        width: 300px;
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
        text-align: center;
        padding: 20px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        margin-left: 30px; /* Add space between the profile and content */
    }
    .profile-box img {
        width: 120px; /* Adjust size */
        height: 120px; /* Adjust size */
        border-radius: 50%;
        object-fit: cover;
        margin-bottom: 15px;
    }
    .profile-box h2 {
        font-size: 1.8em;
        margin: 0;
        font-weight: normal; /* Ensure it's not bold */
        line-height: 1.2;
    }
    .profile-box .keywords {
        background-color: #e6f7ff; /* Softer light blue */
        color: #333;
        font-size: 0.9em;
        padding: 12px;
        border-radius: 8px;
        margin: 15px 0;
        line-height: 1.4;
        font-weight: normal; /* Ensure it's not bold */
    }
    .profile-box .title-container {
        margin-top: 10px;
    }
    .profile-box .title-section {
        background-color: #f0f0f0;
        padding: 12px;
        border-radius: 8px;
        margin-bottom: 8px;
    }
    .profile-box .institution-logo {
        width: 70px ;
        height: auto;
        margin-right: 8px;
        vertical-align: middle;
    }
    .profile-box .title-section p {
        margin: 5px 0;
        font-size: 1em;
        font-weight: normal; /* Ensure it's not bold */
        line-height: 1.3;
    }
    .profile-box .qualification {
        font-size: 0.9em;
        font-style: italic;
        margin-top: 5px;
        font-weight: normal; /* Ensure it's not bold */
    }
    
    /* Content area style */
    .content-area {
        max-width: 800px;
        flex-grow: 1;
    }
    .content-area h1 {
        font-size: 2.4em;
        margin-bottom: 20px;
    }
    .content-area p {
        font-size: 1.1em;
        line-height: 1.6;
        margin-bottom: 20px;
    }
</style>





<div class="container">

    <!-- Content Area (right side) -->
    <div class="content-area">
        <h1>About Me</h1>

        <div class="state-box">
            <p><strong>Current Status:</strong> <em>last updated 01/12/2024</em></p>
            <p>Thesis submitted, preparing my Viva for early December 2024. Starting a Post Doctoral position at Télécom Paris in February 2025. Open to collaborations, feel free to contact me!</p>
        </div>

        <p>I’m a curious researcher with a passion for learning and exploring. In my research, I focuses on how people use space around autonomous drones and explored the use of XR (Extended Reality) as a tool in this field. Recognizing the lack of a theoretical foundation, I developed a model informed by existing proxemic theories, supported by empirical findings collected through user studies. Alongside this, I created guidelines and shared resources to help researchers effectively employ XR in human-drone proxemic studies.</p>
        
        <p>The knowledge and skills I gained throughout my work have also allowed me to collaborate on a variety of exciting projects, from child safety in social VR and authentication techniques for ATMs to enhancing social robot interactions.</p>
        
        <p>Beyond research, my interests are all over the place, keeping me inspired and thinking. These include playing music, reading, woodcarving, programming, video games, films, sports, and learning new languages. Since the time I've written this, I’ve probably engaged in a new personal project.</p>



    </div>

    <!-- Profile Box -->
    <div class="profile-box">
        <img src="assets/moi.jpg" alt="Profile Picture">
        <h2>Robin BRETIN</h2>
        
        <div class="keywords">
            <strong>Keywords:</strong> Human–Drone Interaction, Proxemics, Mixed Reality Application to Research
        </div>
        
        <div class="title-container">
        
            <div class="title-section">
                <img src="https://pbs.twimg.com/profile_images/1178956117403152384/6RH8cW7j_400x400.png" class="institution-logo" alt="Institution Logo">
                <p><strong>Post Doctoral Researcher </strong> at Télécom Paris</p>
                <p class="qualification">(from February 2025)</p>
                <p> XR for Crisis Managment </p>
            </div>

            <div class="title-section">
                <img src="https://pbs.twimg.com/profile_images/1172060955980775424/aXADZOek_400x400.jpg" class="institution-logo" alt="University of Glasgow Logo">
                <p><strong>PhD Student</strong> (Psychology/Computing Science) at University of Glasgow</p>
                <p class="qualification">Graduate in December 2024</p>
            </div>
            
            <div class="title-section">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQh86n1YVfHLDAtUhyLxFdGXSPXVyqfyd6yMg&s" class="institution-logo" alt="ENSC Logo">
                <p><strong>Cognitive Engineer</strong> (since 2020)</p>
            </div>

            
        </div>
    </div>

    
</div>

<style>
    .state-box {
        border: 1px solid;
        background-color: #f4f4f4;
        padding: 10px;
        border-radius: 8px;
        width: fit-content;
        margin: 20px auto;
        font-family: Arial, sans-serif;
    }
    .state-box p {
        margin: 0;
        text-align: left; /* Ensure the text inside the box is aligned left */
        font-size: 0.8em;
    }
</style>



- 📄 [My CV](cv.pdf) - 📚 [Publications](https://scholar.google.com/citations?user=oTu1zfMAAAAJ&hl=fr) - 🖇️ [Contact Me](r.bretin.1@research.gla.ac.uk)


<!-- Separator Line -->
  <hr class="my-4">



<div id="researchCarousel" class="carousel slide mt-4" data-bs-ride="carousel">
  <div class="carousel-inner">
    <!-- First item: Image -->
    <div class="carousel-item active">
      <img src="assets/moi.jpg" class="d-block w-100" alt="First Slide">
      <div class="carousel-caption-below">
        <h5>First Slide Title</h5>
        <p>Short description of the image.</p>
      </div>
    </div>

    <!-- Second item: PDF -->
    <div class="carousel-item">
      <iframe src="assets/protocol.pdf" class="d-block w-100" style="height: 500px;" frameborder="0"></iframe>
      <div class="carousel-caption-below">
        <h5>Second Slide Title</h5>
        <p>Short description of the PDF.</p>
      </div>
    </div>

    <!-- Third item: Image -->
    <div class="carousel-item">
      <img src="assets/chalmers.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>Short description of the image.</p>
      </div>
    </div>

    <div class="carousel-item">
      <iframe src="assets/pathsV3.pdf" class="d-block w-100" style="height: 500px;" frameborder="0"></iframe>
      <div class="carousel-caption-below">
        <h5>Second Slide Title</h5>
        <p>Short description of the PDF.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Overall.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>Short description of the image.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/drones_chalmers.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>Short description of the image.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/VR_room.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>Short description of the image.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Screenshot 2023-09-19 110253.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>Short description of the image.</p>
      </div>
    </div>



  </div>

  <!-- Carousel Controls -->
  <button class="carousel-control-prev" type="button" data-bs-target="#researchCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#researchCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>


<style>
  .carousel-caption-below {
    text-align: center;
    padding: 10px;
    background-color: #f8f9fa; /* Optional: Light gray background */
    border-top: 1px solid #ddd; /* Optional: Separator line */
  }

  .carousel-caption-below h5 {
    margin: 5px 0;
    font-size: 1.25em;
  }

  .carousel-caption-below p {
    margin: 0;
    font-size: 1em;
    color: #666;
  }
</style>


