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
            <p>📌<strong>Current Status:</strong> <em>last updated 01/12/2024</em></p>
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


<!-- Separator Line -->
  <hr class="my-4">

## Research Gallery
Explore a collection of illustrations, graphics, and images from my various projects.


<div id="researchCarousel" class="carousel slide mt-4" data-bs-ride="carousel" data-bs-interval="5000">
  <div class="carousel-inner">
    <!-- First item: Image --> 
    <div class="carousel-item active">
      <img src="assets/path (1)-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Top view of a participant's path as they walk from the starting point (A) around the virtual drone to reach the colored papers (B,C,D) in the room. The sequence of colors to reach appears on the paper (white square) located on the table (blue rectangle) next to the initial position. The circular boundaries around the drone correspond to Hall's framework's intimate and personal spheres, respectively. We notice that the participant follow similar paths but maintain different distances between the conditions.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/pathsV3-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Visualization of participants' trajectories tracked through the VR headset during the task. We've chosen three distinct profiles to emphasize the variability in proxemic sensitivity to the drone's expressions. For clarity, we present paths only for the Follow gaze behaviors, comparing Anger and Sadness expressions. The points where participants paused to initiate conversation are marked by speech logos and circles (red for Anger, orange for Sadness). We can observe that participant A exhibits highly consistent proxemic behavior unaffected by the drone's expressions. In contrast, Participant B exhibits variability primarily within the front zone, maintaining a greater distance when initiating conversation with Anger compared to Sadness. Notably, this difference tends to diminish afterward, possibly illustrating a phenomenon elaborated in the discussion section. This phenomenon suggests that participants may shift their perception of the drone from a social entity to a mere obstacle due to the nature of the assigned task (from engaging in conversation to reaching a point behind it).  Lastly, Participant C exhibits a pronounced influence of the digital facial emotions, remaining visibly important in the front (blue path) and frontal side (yellow path) zones, and diminishing upon return to the starting point. This participant also follows a distinct path to accomplish the task.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Protocol-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>Diagram of participants' Protocol. The process begins after participants have been welcomed and have signed the consent form. Dotted lines indicate steps occurring in the virtual environment, while solid lines represent actions in the real world. (1) Participants provided demographic information and completed the NARS on the experimenter's computer after signing the consent form. (2) Participants received task instructions and specifics of the virtual environment. The experimenter clarified instructions, answered questions, and showed a video demonstration of an explosive box. (3) Participants were immersed in the virtual environment and underwent a practice session without the drone. They performed the experimental task in a simplified environment, allowing them to grab and drop boxes, navigate, and interact with the virtual screen. (4) Participants proceeded with the experimental task by initiating it after reviewing scenario details and clicking "Start". Upon activation, the drone commenced its task, mirroring that of the participants. Participants were tasked with locating and grabbing the highlighted cube, then depositing it within the designated zone. This process repeated for subsequent cubes while avoiding the drone, which occasionally carried explosive boxes. After moving multiple cubes, the drone ceased flying, and the virtual screen reappeared, marking the scenario's end. Participants then answered questions before advancing to the next scenario by clicking "Continue" or removing the headset after completing both scenarios. (5) Participants proceeded to answer the IPQ and FMS on the experimenter's computer. (6) The study concluded with a short semi-directed interview.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/output2.gif" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Animated GIF illustrating participants navigation around a moving flying drone.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/P-visual-V2 (1)-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>A-- After taking a moment to familiarize themselves with the virtual environment, participants stand on the green spot—both the starting point and the interaction zone with virtual screens in the study. B-- From this starting position, participants approach the drone, featuring a combination of Face and Gaze conditions (illustrated here as Sadness and Follow). They initiate communication with a "Hey," signaling their intent. The drone's light turns green, prompting participants to ask for the next letter with "Can you tell me the next letter?" The drone verbally communicates the letter "B," which participants use in the subsequent steps. C--  Participants navigate around the drone to access the screen on its back. D-- On the screen, participants identify the shape corresponding to the letter provided by the drone. In this specific example, the letter "B" corresponds to the correct shape, which is represented by the yellow square as the next element in the shape sequence. E-- Returning to their initial position, participants input the correct shape in the shape sequence. Incorrect inputs can be removed by clicking on them, while correct inputs prompt questions on the left screen. F--Participants, using the controllers, then answer questions, including a Self-Assessment Questionnaire and Likert scales. The study cycle, starting from step A, continues until participants successfully complete the shape sequence, with the sequence's length aligned with the number of distinct sets of conditions.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Rplot06 (1)-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Discomfort level (left) and stop-distance ratings (right) in the real (top) and virtual (bottom) environments for each stop condition. Friedman tests revealed a statistically significant effect of the drone stop distance on participants' discomfort and distance rating in both environments. We can observe an increase in discomfort when entering the personal space (below 120 cm). Overall, the personal space frontier (120cm) was rated the closest to participants' ideal distance (rating of 0) in the real (Md=-3.570) and virtual environment (Md=-10).</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Rplot06 (2)-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Boxplot and violin plots illustrating participants' subjective arousal and maintained distance for the three drone sound level conditions in both task condition. Both significantly increased from the low to high sound level condition in a similar trend.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Rplot06-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Boxplot and violin plots representing participants Total Deviation from the shortest path for each Task Priority and Drone's Danger conditions.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/V4-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Dynamic progression of this thesis, mapping the journey from initial research questions to the development of the main contributions and their interconnections.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/VR_RW environment-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Experimental Room (left) and its replica created in Unity 3D (right).</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/vrr-1.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>The experimental room (left) is shown alongside the mixed-reality environment (right), which combines real-world imagery captured by the VR headset’s camera sensor with additional virtual elements rendered in Unity 3D. These virtual elements include an orange circle on the ground, where participants are required to position themselves during the fixed phase of the task, as well as virtual screens that display questionnaires and task-related information (such as instructions and n-nack digits)</p>
      </div>
    </div>

    <!-- Third item: Image -->
    <div class="carousel-item">
      <img src="assets/chalmers.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>The experimental room (right) next to their virtual replica (left) in Unity 3D. Participants' paths were recorded in the simulation allowing the accurate assessment of proxemic preferences around the drone, in a safe and realistic environment.</p>
      </div>
    </div>


    <div class="carousel-item">
      <img src="assets/Overall.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Overview of the protocol. a- Resting baseline (300s): The drone is on the ground at 450cm from the participant. b- The drone takes off and remains stationary for 60s. c- “Face detection approach”: the drone approaches the participant at the target speed condition (0.25 or 1\,m/s) and stops at the intimate frontier (40cm). d- Static Close: It stays in front of the participant for 60s. e- Distancing procedure: Stop distance and discomfort ratings for 6 predefined drone positions. f- Resting period: The drone lands and rests for 300s. Then the protocol resets to step b for the second speed condition.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/drones_chalmers.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>Some drone designs inspired by Herdel et al. (2021) used in the study: from left to right, representing Surprise, Joy, and Sadness, with diverse gaze behaviors illustrating potential interactions with the drone's digital facial emotions.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/VR_room.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <p>The virtual experimental room depicted in Unity 3D. On the left side of the image, there is a virtual screen providing a description of the current scenario to the participant. Below this screen, a button "Start" is visible, which the participant can click to initiate the task. Numerous cubes were distributed among the chairs and tables in a predefined and consistent manner for both scenarios. Participants are tasked with identifying the highlighted cube among these scattered objects.</p>
      </div>
    </div>

    <div class="carousel-item">
      <img src="assets/Screenshot 2023-09-19 110253.png" class="d-block w-100" alt="Third Slide">
      <div class="carousel-caption-below">
        <h5>Third Slide Title</h5>
        <p>The experimental room and the real Parrot AR.Drone 2.0 (top) next to their virtual replica (bottom) in Unity 3D. Participants' paths were recorded in the simulation, allowing the accurate assessment of proxemic preferences around the drone, in a safe and realistic environment.</p>
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


