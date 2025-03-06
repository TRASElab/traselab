---
layout: page
title: Team
permalink: /team-static/
toggle: on
---

<style>
  /* Styles for the navigation menu */
  .nav {
    display: flex;
    justify-content: center;
    background-color: #f8f9fa;
    padding: 10px;
  }

  .nav-item {
    position: relative;
    padding: 10px 15px;
    cursor: pointer;
  }

  /* Dropdown menu styling */
  .dropdown {
    position: absolute;
    top: 100%;
    left: 0;
    background-color: white;
    display: none;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    z-index: 100;
  }

  .dropdown button {
    display: block;
    width: 200px;
    padding: 10px;
    text-align: left;
    border: none;
    background-color: white;
    color: #333;
    font-size: 16px;
    cursor: pointer;
  }

  .dropdown button:hover {
    background-color: #0073e6;
    color: white;
  }

  /* Show dropdown on hover */
  .nav-item:hover .dropdown {
    display: block;
  }
</style>

<!-- Navigation Menu -->
<div class="nav">
  <div class="nav-item">
    Team
    <div class="dropdown">
      <button onclick="scrollToSection('pi')">Principal Investigator</button>
      <button onclick="scrollToSection('postgraduates')">Postgraduate Students</button>
      <button onclick="scrollToSection('ras')">Research Assistants</button>
    </div>
  </div>
</div>

<script>
  function scrollToSection(id) {
    document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
  }
</script>

## <span id="pi">Principal Investigator</span>
<img src="{{ site.baseurl }}/images/sherrypic.jpeg" alt="Dr. CHAN Kit Wa, Sherry" style="width: 200px; float: right; margin-left: 20px;">
### Dr. CHAN Kit Wa, Sherry
**Clinical Associate Professor**  
- My main research interests are in the evaluation of early intervention service, longitudinal outcomes of psychosis, treatment-resistant schizophrenia, psychopathology (particularly insight and delusion) and its neurobiological basis, metacognition and insight, and psychotic-like experiences.

---

## <span id="postgraduates">Postgraduate Students</span>
**Zhou Huiquan Photon (Postdoctorate Fellow)**
- My research focuses on advancing the understanding of psychosis and developing innovative interventions through clinical and big-data approaches. I aim to explore longitudinal patterns of comorbidities and medications, particularly in treatment-resistant schizophrenia, using predictive modeling and precision medicine to create tailored strategies that reduce adverse outcomes and improve treatment efficacy.

**Harry Tsui (Ph.D Candidate)**
- research interest

**Ciren Zhuoma (Ph.D Candidate)**
- My research interests include youth mental health, self-harm and suicide, and adverse childhood experiences.
  
**Molly Li (Ph.D Candidate)**
- My research focuses on the longitudinal trajectories and outcomes of severe mental illness.

**Charmaine Wong (MPhil Student)**
- research interest

**Sophia (MPhil Student)**
- research interest

---

## <span id="ras">Research Assistants</span>
- Sally Tse
- Victoria Lim
- Fortuna Hau
- Amy Au
- Rachel Ho
- Jace Lo
