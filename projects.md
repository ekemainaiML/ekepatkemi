---
layout: page
title: Projects
permalink: /projects/
image: '/assets/images/lireg1.webp'
---


{% assign postitems = site.posts %}
<html>
    <body class="projects-body">
        <h3 style="text-align: center;">ML, AI, and MLOps</h3>
        <h3 class="project-title" >Prediction of Excitation Current of a Synchronous Motor</h3>
            <p class="project-description">A linear regression model deployed on web app for predicting excitation current of synchronous motors</p>
            <p class="project-description">Skills: Python, DVC, MLEM, Streamlit, IBM Cloud</p>
        <a href="{{ postitems[0].url | relative_url }}">
        <div class="row">
            <div class="column">
                <img src="{{ "/assets/images/proj11.png" | relative_url }}" alt="" class="project-image-one" style="width: 100%;">
            </div>
            <div class="column">
                <img src="{{ "/assets/images/proj12.png" | relative_url }}" alt="" class="project-image-one" style="width:100%; height: 50%">
            </div>
        </div>
        </a>
        <div class="share-page">
            <button id="btn1" class="project-button" type="button">
                <a href="https://github.com/ekemainaiML/ekemainaiMl.github.io.git?text={{ page.title }}&url={{ site.url }}{{ page.url }}&via={{ site.github_username }}&related={{ site.github_username }}" rel="nofollow" target="_blank" title="Code on Github">Code</a>
            </button>
            <button id="btn2" class="project-button" type="button">
                <a href="https://ekemainaiml-syncwebapp-app-aysnd9.streamlit.app?text={{ page.title }}&url={{ site.url }}{{ page.url }}&via={{ site.strealit_username }}&related={{ site.streamlit_username }}" rel="nofollow" target="_blank" title="App on Streamlit Cloud">Deployed App</a>
            </button>
        </div>
    </body>
</html>

