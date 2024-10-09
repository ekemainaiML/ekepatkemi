---
layout: page
title: Certifications
permalink: /certificates/
image: '/assets/images/aronvisuals.jpg'
---

{% assign postitems = site.posts %}
<html>
<style>
    .pdf,
    html,

    h1,
    h3 {
        text-align: center;
    }

    h1 {
        color: green;
    }
</style>
<body class="certificates-body">
       <h1>Coursera Project Network</h1>
       <h3>Introduction to Data Analysis Using Microsoft Excel</h3>
    <div class="columncerts">
       <iframe 
            src="{{ '/assets/docs/Coursera2.pdf' | relative_url }}" 
            width = "100%"
            height="100%">
        </iframe>
    </div>
        <h1>DeepLearning.AI</h1>
       <h3>Linear Algebra For Machine Learning and Data Science</h3>
    <div class="columncerts">
       <iframe 
            src="{{ '/assets/docs/Coursera3.pdf' | relative_url }}" 
            width = "100%"
            height="100%">
        </iframe>
    </div>
        <h1>DeepLearning.AI</h1>
       <h3>Deploying Machine Learning Models in Production</h3>
    <div class="columncerts">
       <iframe 
            src="{{ '/assets/docs/Coursera1.pdf' | relative_url }}" 
            width = "100%"
            height="100%">
        </iframe>
    </div>
        <h1>Google </h1>
       <h3>Foundations of Data Science</h3>
    <div class="columncerts">
       <iframe 
            src="{{ '/assets/docs/Coursera4.pdf' | relative_url }}" 
            width = "100%"
            height="100%">
        </iframe>
    </div>
</body>
</html>

