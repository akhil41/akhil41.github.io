---
title: "Home Intro"
layout: none
permalink: /home-intro/
---

<!-- Minimal styling to center the image and make it circular -->
<div class="mb-2" style="background: transparent !important;">
  <style>
    /* Remove shimmer background if needed */
    .preview-img.shimmer,
    .preview-img.shimmer *,
    .preview-img.shimmer::before,
    .preview-img.shimmer::after,
    .preview-img.shimmer *::before,
    .preview-img.shimmer *::after {
      background: transparent !important;
      background-image: none !important;
      box-shadow: none !important;
      content: none !important;
    }

    /* Container for top buttons */
    .top-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      justify-content: center;
      margin-bottom: 1rem; /* adjust as needed */
    }

    /* The .btn elements inside .top-buttons have no extra margin. */
    .top-buttons .btn {
      margin: 0;
    }

    /* Optionally, reduce or remove margin below the image to tighten spacing. */
    .preview-img img {
      margin-bottom: 0.75rem !important; /* was 1rem before */
    }
  </style>

  <!-- 1) Random Buttons at the top (no <br>, just let flex-wrap do the wrapping) -->
  
  <!-- 2) Circular image section (no shimmer background) -->
  <!-- Instead of .preview-img, call it .my-image-wrapper -->
<!-- Instead of .preview-img shimmer, just use your own class, e.g. .my-image-wrapper -->
<div class="my-image-wrapper" style="text-align:center;">
  <img 
    src="/assets/images/profile_photo.jpg"
    alt="Akhil Chaudhary"
    style="
      width: 250px;
      height: 250px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid var(--card-bg);
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      background: transparent !important;
      margin-bottom: 0;"
    loading="lazy"
  />
</div>
<div class="top-buttons">
    <a href="/tags/nlp/" class="btn btn-outline-primary">💬 NLP</a>
    <a href="/tags/kg/" class="btn btn-outline-primary">🕸️ KG</a>
    <a href="/tags/reasoning/" class="btn btn-outline-primary">Reasoning</a>
    <a href="/tags/modeling/" class="btn btn-outline-primary">⚙️ Modeling</a>
    <a href="/tags/ml/" class="btn btn-outline-primary">🤓 ML Concepts</a>
    <a href="/tags/dl/" class="btn btn-outline-primary">🤯 DL Concepts</a>
    <a href="/tags/multimodel/" class="btn btn-outline-primary">🗂️ Multimodel</a>
    <a href="/tags/mlops/" class="btn btn-outline-primary">🚁 ML Ops</a>
    <a href="/tags/tools/" class="btn btn-outline-primary">🪛 Tool Recommendations</a>
  </div>

</div>

#### 👋🏽 Hey, I'm Akhil Chaudhary
I like to leverage knowledge graph to train deep neural nets on large datasets and build explainable AI systems. 
I've attended Dalhousie University and serve as a research fellow at Dalhousie, Saint Marys University, and Cape Breton University.
My interests include reasoning, explainability, information reitrieval, natural language processing, and cricket....










<div class="timeline-container">
  <style>
    .timeline-container {
      position: relative;
      padding: 2rem 0;
    }

    .timeline {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      position: relative;
      width: 90%;
      max-width: 800px;
      margin: 0 auto;
    }

    /* Add the vertical timeline line */
    .timeline::before {
      content: "";
      position: absolute;
      left: 130px; /* Aligns with the date column */
      top: 0;
      bottom: 0;
      width: 2px; /* Thinner line */
      background-color:rgb(112, 130, 150); /* Primary color for the line */
      z-index: 0;
    }

    .timeline-item {
    display: flex;
    align-items: center; /* Aligns items vertically */
    margin-bottom: 2rem;
    position: relative;
    width: 100%;
    }

    /* Add bullets to each timeline entry */
    .timeline-item::before {
      content: "";
      position: absolute;
      left: 126px; /* Aligns the bullet with the timeline line */
      top: 10px; /* Centers the bullet vertically with the date */
      width: 10px; /* Bullet size */
      height: 10px; /* Bullet size */
      background-color:rgb(172, 123, 200); /* Primary color for the bullet */
      border-radius: 50%; /* Makes the bullet a circle */
      z-index: 1; /* Ensures it sits above the line */
    }

    .timeline-date {
      flex: 0 0 120px;
      font-weight: bold;
      font-size: 1.1rem;
      color:rgb(138, 141, 143);
      text-align: right;
      margin-right: 1rem;
      z-index: 1; /* Ensures the date is above the line */
    }

    .timeline-content {
    display: flex;
    align-items: center; /* Aligns image and text vertically */
    justify-content: flex-start; /* Ensures text is on the right of the image */
    flex: 1;
    padding-left: 2rem;
    position: relative;
    }

    .timeline-image {
    flex: 0 0 70px; /* Ensures consistent width for the image container */
    height: 70px; /* Sets a consistent height for the image container */
    display: flex;
    align-items: center; /* Centers the image vertically */
    justify-content: center; /* Centers the image horizontally */
    margin-right: 1rem; /* Adds space between image and text */
    overflow: hidden; /* Prevents overflow issues */
    }

    .timeline-image img {
    max-width: 100%; /* Ensures the image fits within the container's width */
    max-height: 100%; /* Ensures the image fits within the container's height */
    object-fit: contain; /* Preserves the aspect ratio and ensures the entire image is visible */
    display: block; /* Removes any inline spacing around the image */
    }




    .timeline-description {
      flex: 1;
    }

    .timeline-description p {
      margin: 0.5rem 0;
    }

    .timeline-description a {
      text-decoration: none;
      color:rgb(59, 101, 200);
      font-weight: bold;
    }

    .timeline-description a:hover {
      text-decoration: underline;
    }
  </style>

  <div class="timeline">
    <!-- Item 1 -->
    <div class="timeline-item">
      <div class="timeline-date">2024 - Present</div>
      <div class="timeline-content">
        <div class="timeline-image">
          <img src="https://www.goxgo.ca/assets/Primary_Logo_-_.5x.png" alt="StFX Logo" style="width: 70px; height: 70px; object-fit: contain;" />
        </div>
        <div class="timeline-description">
          <p><strong>Research Project Manager</strong> at <a href="https://www.stfx.ca" target="_blank">St. Francis Xavier University</a></p>
          <p>Leading machine learning and neuroimaging research projects, including developing automated multiverse analysis tools.</p>
        </div>
      </div>
    </div>

    <!-- Item 2 -->
    <div class="timeline-item">
      <div class="timeline-date">2023 - Present</div>
      <div class="timeline-content">
        <div class="timeline-image">
          <img src="https://www.cbu.ca/wp-content/uploads/2020/06/CBU-ShieldLogo_orange.png" alt="CBU Logo" />
        </div>
        <div class="timeline-description">
          <p><strong>Research Fellow and Sessional Instructor</strong> at <a href="https://www.cbu.ca" target="_blank">Cape Breton University</a></p>
          <p>Teaching and conducting research in Explainable AI, Knowledge Graphs, and usability of LLMs in structured data.</p>
        </div>
      </div>
    </div>

    <!-- Item 3 -->
    <div class="timeline-item">
      <div class="timeline-date">2023 - 2024</div>
      <div class="timeline-content">
        <div class="timeline-image">
          <img src="https://static.wixstatic.com/media/4a2ba4_11cfa91de04f4a3884d6e455bc317929~mv2.png/v1/crop/x_77,y_7,w_913,h_272/fill/w_544,h_162,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/Gyan%20Logo.png" alt="Gyan AI Logo" />
        </div>
        <div class="timeline-description">
          <p><strong>Data Scientist</strong> at <a href="https://www.gyan.ai" target="_blank">Gyan AI</a></p>
          <p>Led Knowledge Graph-based explainable LLM research and backend development for university ERP systems.</p>
        </div>
      </div>
    </div>

    <!-- Item 4 -->
    <div class="timeline-item">
      <div class="timeline-date">2022 - 2023</div>
      <div class="timeline-content">
        <div class="timeline-image">
          <img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/c3/Dalhousie_University_Seal.svg/300px-Dalhousie_University_Seal.svg.png" alt="Dalhousie Logo" />
        </div>
        <div class="timeline-description">
          <p><strong>Research Assistant</strong> at <a href="https://www.dal.ca" target="_blank">Dalhousie University</a></p>
          <p>Thesis: Top2Label - Explainable Zero-Shot Topic Labelling Using Knowledge Graphs.</p>
        </div>
      </div>
    </div>

    <!-- Item 5 -->
    <div class="timeline-item">
      <div class="timeline-date">2020 - 2021</div>
      <div class="timeline-content">
        <div class="timeline-image">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Accenture.svg/440px-Accenture.svg.png" alt="Accenture Logo" />
        </div>
        <div class="timeline-description">
          <p><strong>Data Scientist</strong> at <a href="https://www.accenture.com" target="_blank">Accenture</a></p>
          <p>Developed scalable deep learning pipelines and transformer-based NLP models for customer feedback analysis.</p>
        </div>
      </div>
    </div>

    <!-- Item 6 -->
    <div class="timeline-item">
      <div class="timeline-date">2018 - 2020</div>
      <div class="timeline-content">
        <div class="timeline-image">
          <img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/30/Allstate_logo.svg/440px-Allstate_logo.svg.png" alt="Allstate Logo" />
        </div>
        <div class="timeline-description">
          <p><strong>Data Science Consultant</strong> at <a href="https://www.allstate.com" target="_blank">Allstate</a></p>
          <p>Invented a blur detection algorithm and automated millions of claims processing operations.</p>
        </div>
      </div>
    </div>
  </div>
</div>
