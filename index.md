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
<br/>




<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News Slider</title>
    <style>
        #updates {
            background-color: #32012F; /* Dark background */
            padding: 20px; /* Add padding */
            color: #fff; /* White text for better contrast */
        }

        .update-container {
            overflow: hidden; /* Handle content overflow */
            width: 100%; /* Full width */
            position: relative; /* Positioning for updates */
            height: 300px; /* Adjust height to fit three updates */
        }

        .update {
            position: absolute; /* Absolute positioning */
            top: 0;
            width: 100%; /* Full width */
            transition: transform 0.5s ease-in-out, opacity 0.5s ease-in-out; /* Transition effect */
            opacity: 0; /* Initially hidden */
            padding: 10px; /* Padding for better look */
            box-sizing: border-box; /* Include padding in width */
        }

        .update.active {
            opacity: 1; /* Show active update */
            transform: translateX(0); /* Position for active update */
        }

        .update.inactive {
            opacity: 0; /* Hide inactive updates */
            transform: translateX(100%); /* Off-screen position */
        }

        #prev-update, #next-update {
            display: none; /* Hide buttons initially */
            background-color: #fff; /* White background */
            color: #32012F; /* Dark text */
            border: none; /* Remove border */
            padding: 10px; /* Padding for buttons */
            cursor: pointer; /* Pointer cursor */
        }

        @media (hover: hover) { /* Show buttons on hover */
            #updates:hover #prev-update, 
            #updates:hover #next-update {
                display: inline-block; /* Show buttons on hover */
            }
        }
    </style>
</head>
<body>
    <section id="updates">
        <h3>Updates/News</h3>
        <div class="update-container">
            <div class="update active">
                <h4>(06/24) Presented an in-person poster on "MATHSENSEI: A Tool-Augmented Large Language Model for Mathematical Reasoning" at NAACL 2024 Mexico City</h4>
            </div>
            <div class="update active">
                <h4>(04/24) Accepted as a CS PHD Student at UMass Amherst - advised by Negin Rahimi!</h4>
            </div>
            <div class="update active">
                <h4>(12/23) Completed my internship at Rakuten Global Inc., Language and Speech Team, RIT India.</h4>
            </div>
            <div class="update inactive">
                <h4>(11/23) Published a paper in IEEE Transactions on Neural Networks and Learning Systems.</h4>
            </div>
            <div class="update inactive">
                <h4>(10/23) Presented at the ACM Multimedia Conference 2023 in Ottawa, Canada.</h4>
            </div>
            <div class="update inactive">
                <h4>(09/23) Joined the AI Research Team at Google as a Research Intern.</h4>
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
        const visibleCount = 3; // Number of visible updates
        const intervalTime = 5000; // Time interval in milliseconds

        function showUpdates() {
            updates.forEach((update, i) => {
                if (i >= currentIndex && i < currentIndex + visibleCount) {
                    update.classList.add('active');
                    update.classList.remove('inactive');
                } else {
                    update.classList.remove('active');
                    update.classList.add('inactive');
                }
            });
        }

        prevButton.addEventListener('click', () => {
            currentIndex = (currentIndex - visibleCount + updates.length) % updates.length;
            showUpdates();
        });

        nextButton.addEventListener('click', () => {
            currentIndex = (currentIndex + visibleCount) % updates.length;
            showUpdates();
        });

        function autoSlide() {
            nextButton.click();
        }

        let slideInterval = setInterval(autoSlide, intervalTime);

        // Pause auto sliding on mouse hover
        document.getElementById('updates').addEventListener('mouseenter', () => {
            clearInterval(slideInterval);
        });

        // Resume auto sliding on mouse leave
        document.getElementById('updates').addEventListener('mouseleave', () => {
            slideInterval = setInterval(autoSlide, intervalTime);
        });

        // Initially show the first set of updates
        showUpdates();
    </script>
</body>
</html>



  
