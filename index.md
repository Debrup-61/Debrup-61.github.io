---
layout: page
---

<div class="bio-container">
  <div style="flex: 0 0 30%; text-align: left;">
    <img src="debrup.png" alt="Description of image" style="max-width: 80%; height: auto;">
  </div>
  <div class="bio-text">
    
   I am a 1st year Computer Science PhD student at the <a href="https://www.cics.umass.edu/">Manning College of Information & Computer Science</a>, <a href="https://www.umass.edu/">University of Massachusetts Amherst</a>. I am advised by  <a href="https://people.cs.umass.edu/~rahimi/">Prof. Negin Rahimi</a>. My broad research interests are primarily in Information Retrieval (IR) and Natural Language Processing (NLP). Prior to this, I received a Dual Degree (Bachelors + Masters) in Mathematics and Computing from IIT Kharagpur, India where I worked on the paradigm of tool-augmentation for mathematical reasoning in LLMs, supervised by <a href="https://adityasomak.github.io/">Prof. Somak Aditya</a>.
    <br/><br/>
    My current research interests are focused on the effective utilization of retrieval-based systems and external structured knowledge to improve multiple reasoning dimensions in language models. My other interests revolve around the use of neuro-symbolic methods in NLP, and trying to make LLMs safer to use in social contexts.
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
          padding: 20px;
          color: #2c3e50; /* dark slate for text */
          font-family: "Segoe UI", Arial, sans-serif; /* modern readable font */
        }
        
        .update {
          background-color: #ffffff; /* pure white cards */
          border: 1px solid #e0e0e0; /* subtle cool gray border */
          border-radius: 10px;
          padding: 15px;
          margin-bottom: 12px;
          box-shadow: 0px 2px 6px rgba(0,0,0,0.08); /* soft professional shadow */
          transition: transform 0.2s ease, box-shadow 0.2s ease; /* hover effect */
        }
        
        /* Hover effect for interactivity */
        .update:hover {
          transform: translateY(-2px);
          box-shadow: 0px 4px 12px rgba(0,0,0,0.12);
        }
        
        /* Links inside updates */
        .update a {
          color: #0056b3; /* modern blue accent */
          font-weight: 500;
          text-decoration: none;
        }
        .update a:hover {
          text-decoration: underline;
        }
    </style>
</head>

<body>
  <section id="updates">
    <h3>Updates/News</h3>
    <div class="update-list">
      <div class="update">
        <h4>(09/24) Started my PHD at UMass Amherst - advised by Prof. Negin Rahimi!</h4>
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
      <div class="update">
        <h4>(06/23) Started working on Hate speech and Jailbreaks as part of 
          <a href="https://www.microsoft.com/en-us/research/collaboration/accelerating-foundation-models-research/">Microsoft AFMR Program</a>, 
          advised by Prof Somak Aditya (IIT KGP) and 
          <a href="https://mbzuai.ac.ae/study/faculty/monojit-choudhury/">Prof Monojit Choudhury (MBZUAI)</a>.
        </h4>
      </div>
      <div class="update">
        <h4>(12/22) Completed my research internship at Genome Quebec Innovation Centre, 
          <a href="https://www.mcgill.ca/">McGill University</a> - supervised by 
          <a href="https://www.mcgillgenomecentre.ca/investigators/simon-gravel/">Prof. Simon Gravel</a>.
        </h4>
      </div>
      <div class="update">
        <h4>(05/21) Worked in the field of Genetic Algorithms, supervised by 
          <a href="https://www.linkedin.com/in/nirupam-chakraborti-4679371a9/">Prof Nirupam Chakraborti</a>.
        </h4>
      </div>
    </div>
  </section>
</body>
</html>
