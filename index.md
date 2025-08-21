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
            background-color: #f9f9f9; /* Light background */
            padding: 20px;
            color: #222; /* Dark text */
        }
        
        .update {
            background-color: #ffffff; /* White cards */
            color: #222;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 10px;
            margin-bottom: 10px;
            box-shadow: 0px 2px 4px rgba(0,0,0,0.1); /* subtle card shadow */
        }
        
        #prev-update, #next-update {
            display: none;
            background-color: #0066cc; /* Blue buttons */
            color: #fff;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 6px;
        }
        
        @media (hover: hover) {
            #updates:hover #prev-update, 
            #updates:hover #next-update {
                display: inline-block;
            }
        }

    </style>
</head>
<body>
    <section id="updates">
        <h3>Updates/News</h3>
        <div class="update-container">
            <div class="update active">
                <h4>(09/24) Started my PHD at UMass Amherst - advised by Prof. Negin Rahimi !</h4>
                <h4>(06/24) Presented my main conference paper on <a href="https://aclanthology.org/2024.naacl-long.54/">"MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning"</a> at <a href="https://2024.naacl.org/">NAACL 2024</a>, Mexico City.</h4>
          <h4>(12/23) Completed my internship at <a href="https://global.rakuten.com/corp/">Rakuten Global Inc.</a>, Language and Speech Team, RIT India.</h4>
            </div>

           <div class="update inactive">
           <h4>(06/23) Started working on Hate speech and Jailbreaks as part of <a href="https://www.microsoft.com/en-us/research/collaboration/accelerating-foundation-models-research/">Microsoft AFMR Program</a>, advised by Prof Somak Aditya (IIT KGP) and <a href="https://mbzuai.ac.ae/study/faculty/monojit-choudhury/">Prof Monojit Choudhury (MBZUAI)</a>.</h4>
           <h4>(12/22) Completed my research internship at Genome Quebec Innovation Centre, <a href="https://www.mcgill.ca/">McGill University</a> - supervised by <a href="https://www.mcgillgenomecentre.ca/investigators/simon-gravel/">Prof. Simon Gravel</a>.</h4>
            <h4>(05/21) Worked in the field of Genetic Algorihtms, supervised by <a href="https://www.linkedin.com/in/nirupam-chakraborti-4679371a9/">Prof Nirupam Chakraborti</a>.</h4>
           </div>
        </div>
        <button id="prev-update">&#8592;</button>
        <button id="next-update">&#8594;</button>
    </section>

    <script>
        const updates = document.querySelectorAll('.update');
        const prevButton = document.getElementById('prev-update');
        const nextButton = document.getElementById('next-update');
        let currentIndex = 0;

        function showUpdate(index) {
            updates.forEach((update, i) => {
                if (i === index) {
                    update.classList.add('active');
                    update.classList.remove('inactive');
                } else {
                    update.classList.remove('active');
                    update.classList.add('inactive');
                }
            });
        }

        prevButton.addEventListener('click', () => {
            currentIndex = (currentIndex > 0) ? currentIndex - 1 : updates.length - 1;
            showUpdate(currentIndex);
        });

        nextButton.addEventListener('click', () => {
            currentIndex = (currentIndex < updates.length - 1) ? currentIndex + 1 : 0;
            showUpdate(currentIndex);
        });

        // Initially show the first update
        showUpdate(currentIndex);
    </script>
</body>
</html>
