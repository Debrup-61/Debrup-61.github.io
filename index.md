---
layout: page
---

<div class="bio-container">
  <div style="flex: 0 0 30%; text-align: left;">
    <img src="debrup2.jpg" alt="Description of image" style="max-width: 80%; height: auto;">
  </div>
  <div class="bio-text">
    
   I am a 1st year Computer Science PhD student at the <a href="https://www.cics.umass.edu/">Manning College of Information & Computer Science</a>, <a href="https://www.umass.edu/">University of Massachusetts Amherst</a>. I am advised by  <a href="https://people.cs.umass.edu/~rahimi/">Prof. Negin Rahimi</a>. My broad research interests are primarily in Information Retrieval (IR) and Natural Language Processing (NLP). Prior to this, I received a Dual Degree (Bachelors + Masters) in Mathematics and Computing from IIT Kharagpur, India where I worked on the paradigm of tool-augmentation for mathematical reasoning in LLMs, supervised by <a href="https://adityasomak.github.io/">Prof. Somak Aditya</a>.
    <br/><br/>
    My overarching research goals are focused on the effective utilization of retrieval-based systems and external structured knowledge to improve multiple reasoning dimensions in LLMs. Currently, I am interested in developing advanced retrieval systems for reasoning-intensive tasks, where retrievers perform multi-step, complex reasoning across multiple turns, leveraging both intermediate outputs and previously retrieved information. I am working on agentic retrieval frameworks, using reinforcement learning to train retrievers with step-wise feedback in dynamic environments. My other research interests revolve around the use of neuro-symbolic methods in NLP, and trying to make LLMs safer to use in social contexts.
  </div>
</div>
<br/>



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News Slider</title>
    <style>


        /* Whole page background */
        body {
            background-color: #ffffff !important; /* White background */
            color: #222 !important; /* Dark text */
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        
        /* Top toolbar / navigation bar */
        header, nav, .site-header, .navbar {
            background-color: #f9f9f9 !important; /* Light gray toolbar */
            color: #222 !important; /* Dark text */
        }
        
        /* Toolbar links */
        header a, nav a, .site-header a, .navbar a {
            color: #0066cc !important; /* Blue links */
            text-decoration: none;
        }
        header a:hover, nav a:hover, .site-header a:hover, .navbar a:hover {
            text-decoration: underline;
        }


        
        /* Bio section (your intro with image) */
        .bio-container {
            display: flex;
            align-items: center;
            background-color: #f9f9f9; /* Soft light background */
            padding: 20px;
            border-bottom: 1px solid #ddd;
        }
        
        .bio-container img {
            max-width: 80%;
            height: auto;
            border-radius: 8px; /* Smooth edges */
        }
        
        .bio-text {
            flex: 1;
            margin-left: 40px;
        }
        
        /* Updates Section */
                    #updates {
        background-color: #f8f9fa; /* clean light gray */
        padding: 15px 20px;
        color: #2c3e50; /* dark slate */
        font-family: "Segoe UI", Arial, sans-serif;
      }
      
      .update {
        background-color: transparent; /* no separate card */
        border-left: 3px solid #0056b3; /* subtle accent line */
        padding: 5px 10px;
        margin: 6px 0;
      }
      
      .update h4 {
        margin: 0; /* remove extra spacing */
        font-size: 15px; /* slightly smaller text */
        font-weight: 400;
        line-height: 1.4;
      }
      
      .update a {
        color: #0056b3;
        text-decoration: none;
        font-weight: 500;
      }
      .update a:hover {
        text-decoration: underline;
      }

        #publications {
        padding: 40px 20px;
        background-color: #f9f9f9;
        color: #2c3e50;
        font-family: "Segoe UI", Arial, sans-serif;
      }
      
      #publications h2 {
        text-align: center;
        margin-bottom: 30px;
        color: #0056b3; /* professional accent color */
      }
      
      .publication {
        display: flex;
        align-items: flex-start;
        margin-bottom: 25px;
        gap: 20px; /* spacing between image and details */
      }
      
      .pub-image img {
        width: 120px;  /* adjust size as needed */
        height: auto;
        object-fit: contain;
        border-radius: 6px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.08);
      }
      
      .pub-details h3 {
        margin: 0 0 5px 0;
        font-size: 18px;
        font-weight: 600;
        color: #0056b3; /* same accent as section header */
      }
      
      .pub-details p {
        margin: 0;
        font-size: 14px;
        line-height: 1.5;
      }
      
      @media (max-width: 768px) {
        .publication {
          flex-direction: column;
          align-items: center;
          text-align: center;
        }
        .pub-image img {
          width: 80%;
        }
      }




    </style>
</head>

<body>
  <section id="updates">
    <h3>Updates/News</h3>
    <div class="update-list">
      <div class="update">
        <h4>(08/25) <a href="https://arxiv.org/abs/2505.18405"> RaDeR: Reasoning-aware Dense Retrieval Models</a> accepted as Main Conference Paper at EMNLP 2025, Suzhao, China! </h4>
      </div>
      
      <div class="update">
        <h4>(09/24) Started my PHD at UMass Amherst - advised by Prof. Negin Rahimi!</h4>
      </div>
      <div class="update">
        <h4>(04/25)
          Joint work with <a href="https://mbzuai.ac.ae/">MBZUAI</a>, <a href="https://aclanthology.org/2025.naacl-long.463/">"SMAB: MAB based word Sensitivity Estimation Framework and its Applications in Adversarial Text Generation"</a> accepted as Main Conference paper at <a href="">NAACL 2025</a>, New Mexico.
        </h4>
      </div>
      
      <div class="update">
        <h4>(06/24) Presented my main conference paper on 
          <a href="https://aclanthology.org/2024.naacl-long.54/">"MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning"</a> 
          at <a href="https://2024.naacl.org/">NAACL 2024</a>, Mexico City.
        </h4>
      </div>
      <div class="update">
        <h4>(12/23) Completed my internship at 
          <a href="https://global.rakuten.com/corp/">Rakuten Global Inc.</a>, Language and Speech Team, RIT India.
        </h4>
      </div>
  </div>    
  
  </section>

  <section id="publications">
  <h2>Publications</h2>

  <div class="publication">
    <div class="pub-image">
      <img src="rader.png" alt="Paper 1 Figure">
    </div>
    <div class="pub-details">
      <h3>RaDeR: Reasoning-aware Dense Retrieval Models</h3>
      <p>
         <strong>Debrup Das</strong>, Sam O' Nuallain, Razieh Rahimi
        <br>
        <em>Main Conference Paper at EMNLP 2025, Suzhao, China </em>
      </p>
    </div>
  </div>

  <div class="publication">
    <div class="pub-image">
      <img src="mathsensei.png" alt="Paper 2 Figure">
    </div>
    <div class="pub-details">
      <h3>MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning</h3>
      <p>
        <strong>Debrup Das</strong>, Debopriyo Banerjee, Somak Aditya, Ashish Kulkarni
        <em>Main Conference Paper at NAACL 2024, Mexico City</em>
      </p>
    </div>
  </div>

  <!-- Add more publications in the same format -->
  <div class="publication">
    <div class="pub-image">
      <img src="smab.png" alt="Paper 3 Figure">
    </div>
    <div class="pub-details">
      <h3>SMAB: MAB based word Sensitivity Estimation Framework and its Applications in Adversarial Text Generation</h3>
      <p>
        Saurabh Kumar Pandey, Sachin Vashistha, <strong>Debrup Das</strong>, Somak Aditya, Monojit Choudhury
        <em>Main Conference Paper at NAACL 2025, New Mexico</em>
      </p>
    </div>
  </div>


</section>


</body>


</html>
