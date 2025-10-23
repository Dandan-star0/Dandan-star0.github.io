
---
layout: default
title: "Research"
---

<nav>
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/publications">Publications</a>
  <a href="/cv">CV</a>
</nav>

<button class="theme-toggle" onclick="toggleTheme()">🌓</button>

<script>
  function toggleTheme() {
    const body = document.body;
    const currentTheme = body.getAttribute('data-theme');
    const newTheme = currentTheme === 'dark' ? 'light' : 'dark';
    body.setAttribute('data-theme', newTheme);
    localStorage.setItem('theme', newTheme);
  }
  // Load stored theme
  const savedTheme = localStorage.getItem('theme') || 'light';
  document.body.setAttribute('data-theme', savedTheme);
</script>




# 🔭 Research Overview

My research focuses on the **evolution and explosion of massive binary stars**.  
Through a combination of analytic theory, numerical simulation, and stellar population modelling, I explore how binary interactions shape the fates of massive stars and produce diverse transients and compact objects.

---

### Massive Binary Evolution
I investigate how binary mass transfer, common-envelope evolution, and orbital dynamics lead to the formation of **gravitational-wave progenitors** and **stripped-envelope supernovae**.

---

### Core-Collapse Supernovae
I model **shock propagation and light curve evolution** of core-collapse SNe interacting with circumstellar material (CSM), using both analytic and numerical methods.

---

### Multiple Populations in Globular Clusters
I explore how binary interactions and stellar feedback contribute to the observed **chemical and photometric anomalies** in multiple stellar populations of globular clusters.
