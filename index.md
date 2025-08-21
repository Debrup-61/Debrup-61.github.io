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
  
  </section>
</body>
</html>
