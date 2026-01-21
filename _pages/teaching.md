---
layout: page
permalink: /teaching/
title: Teaching & Supervision
description: Courses I've taught and master's theses I've supervised.
nav: true
nav_order: 6
---

<style>
  .course-card {
    transition: transform 0.2s, box-shadow 0.2s;
    border: none;
    background-color: #fff;
    border: 1px solid rgba(0,0,0,0.05);
  }
  .course-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.08) !important;
  }
  .course-icon {
    font-size: 2.5rem;
    color: #e0e0e0;
    margin-bottom: 1rem;
    transition: color 0.3s;
  }
  .course-card:hover .course-icon {
    color: #007bff;
  }
  
  /* Thesis Timeline Style */
  .thesis-item {
    border-left: 2px solid #e9ecef;
    padding-left: 20px;
    padding-bottom: 30px;
    position: relative;
  }
  .thesis-item:last-child { padding-bottom: 0; }
  .thesis-item::before {
    content: '';
    width: 12px;
    height: 12px;
    background: #fff;
    border: 2px solid #007bff;
    border-radius: 50%;
    position: absolute;
    left: -7px;
    top: 5px;
  }
  .thesis-year {
    font-size: 0.8rem;
    font-weight: bold;
    color: #adb5bd;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 5px;
    display: block;
  }
  .thesis-title { font-weight: 600; color: #333; }
  .thesis-students { font-size: 0.95rem; color: #555; }
</style>

## 📚 Courses

<div class="row">
  <div class="col-md-4 mb-3">
    <div class="card h-100 shadow-sm course-card p-3">
      <div class="card-body text-center">
        <i class="fas fa-brain course-icon"></i>
        <h5 class="card-title">Machine Learning for NLP</h5>
        <p class="card-text mb-1 badge bg-light text-dark">Study Period 2</p>
        <p class="card-text text-muted small mt-2">2022, 2023, 2024</p>
      </div>
    </div>
  </div>
  <div class="col-md-4 mb-3">
    <div class="card h-100 shadow-sm course-card p-3">
      <div class="card-body text-center">
        <i class="fas fa-robot course-icon"></i>
        <h5 class="card-title">Applied Machine Learning</h5>
        <p class="card-text mb-1 badge bg-light text-dark">Study Period 4</p>
        <p class="card-text text-muted small mt-2">2022, 2023, 2024, 2025</p>
      </div>
    </div>
  </div>
  <div class="col-md-4 mb-3">
    <div class="card h-100 shadow-sm course-card p-3">
      <div class="card-body text-center">
        <i class="fas fa-chart-area course-icon"></i> <h5 class="card-title">Intro to Data Science & AI</h5>
        <p class="card-text mb-1 badge bg-light text-dark">Study Period 1</p>
        <p class="card-text text-muted small mt-2">2022, 2023</p>
      </div>
    </div>
  </div>
</div>

<hr style="margin: 3rem 0; opacity: 0.1;">

## 🎓 Master's Thesis Supervision

<div class="mt-4">
  <div class="thesis-item">
    <span class="thesis-year">2025–2026</span>
    <div class="thesis-title">How Far Is Too Far? Temporal Memory Limits in Large Language Models</div>
    <div class="thesis-students">Ahmed Yasser, Franziska Penzkofer</div>
    <div class="small text-muted"></div>
  </div>
  <div class="thesis-item">
    <span class="thesis-year">2025–2026</span>
    <div class="thesis-title">Vectorizing Tabular Data for RAG and Vector Database Validation</div>
    <div class="thesis-students">Eric Källman, Max Sjödahl</div>
    <div class="small text-muted">Co-supervisors: Adam Ek, AI Sweden</div>
  </div>

  
  <div class="thesis-item">
    <span class="thesis-year">2024–2025</span>
    <div class="thesis-title">Methods for Optimizing BERT on Edge Devices</div>
    <div class="thesis-students">Atefeh Mirzabeigi, Amir Ali Barani</div>
    <div class="small text-muted">Co-supervisors: Miguel Carmona, Michaël Ughetto, AstraZeneca</div>
  </div>
  <div class="thesis-item">
    <span class="thesis-year">2024–2025</span>
    <div class="thesis-title">Behavioral Control of Memory in LLMs</div>
    <div class="thesis-students">Franziska Penzkofer</div>
  </div>

  <div class="thesis-item">
    <span class="thesis-year">2024–2025</span>
    <div class="thesis-title">Tracing Factual Memory Across Modalities</div>
    <div class="thesis-students">Luca Modica, Filip Landin</div>
  </div>

  <div class="thesis-item">
    <span class="thesis-year">2023–2024</span>
    <div class="thesis-title">Extracting Key Sentences from CRISPR-Cas9 Articles</div>
    <div class="thesis-students">Sandra Henningsson, Brage Nicolay Lae</div>
    <div class="small text-muted">Co-supervisor: Rasool Saghaleyni</div>
  </div>

</div>