---
layout: page
---

<div style="display: flex; align-items: center;">
  <div style="flex: 0 0 30%; text-align: left;">
    <img src="debrup.png" alt="Description of image" style="max-width: 80%; height: auto;">
  </div>
  <div style="flex: 1; margin-left: 40px;">
    
   I am a 1st year Computer Science PhD student at the <a href="https://www.cics.umass.edu/">Manning College of Information & Computer Science</a>, <a href="https://www.umass.edu/">University of Massachusetts Amherst</a>. I am advised by  <a href="https://people.cs.umass.edu/~rahimi/">Prof. Negin Rahimi</a>. My broad research interests are primarily in Information Retrieval (IR) and Natural Language Processing (NLP). Prior to this, I received a Dual Degree (Bachelors + Masters) in Mathematics and Computing from IIT Kharagpur, India where I worked on the paradigm of tool-augmentation for mathematical reasoning in LLMs, supervised by <a href="https://adityasomak.github.io/">Prof. Somak Aditya</a>.
    <br/><br/>
    My current research interests are focused on the effective utilization of retrieval-based systems and external structured knowledge to improve multiple reasoning dimensions in language models. My other interests revolve around the use of neuro-symbolic methods in NLP, and trying to make LLMs safer to use in social contexts.
  </div>
</div>

<section id="updates">
  <h3>Updates/News</h3>
  <div class="update-container">
    <div class="update active">  <h4>(06/24) Presented an in-person poster on "MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning" at NAACL 2024 Mexico City</h4>
    </div>
    <div class="update">
      <h4>(04/24) Accepted as a CS PHD Student at UMass Amherst - advised by Negin Rahimi!</h4>
    </div>
    <div class="update">
      <h4>(12/23) Completed my internship at Rakuten Global Inc., Language and Speech Team, RIT India.</h4>
    </div>
  </div>
  <button id="prev-update">&#8592;</button>
  <button id="next-update">&#8594;</button>
</section>

<style>

#updates {
  background-color: #973131; /* Brown background */
  padding: 20px; /* Add some padding for better readability */
}
  
.update-container {
  overflow: hidden; /* This is important for handling content overflow */
  width: 100%; /* Adjust width as needed */
  position: relative; /* Needed for absolute positioning of updates */
}

.update {
  position: absolute;  /* Make updates absolute for transition effect */
  top: 0;
  left: 0;
  width: 100%;  /* Ensure updates fill the container width */
  transition: transform 0.5s ease-in-out; /* Add transition effect */
  opacity: 0;  /* Initially hide all updates */
  padding: 10px; /* Add some padding for better look */
  border-bottom: 1px solid #ddd; /* Add a border for separation */
}

.update.active {
  opacity: 0.4;  /* Make the first update visible */
  transform: translateX(0); /* Set initial position for active update */
}

.update:not(.active) {
  transform: translateX(100%); /* Position inactive updates off-screen */
}

#prev-update, #next-update {
  /* Style navigation buttons as needed */
  display: none; /* Hide buttons initially */
}

@media (hover: hover) { /* Show buttons on hover for better UX  */
  #updates:hover #prev-update, 
  #updates:hover #next-update {
    display: inline-block; /* Show buttons on hover */
  }
}
</style>



  
