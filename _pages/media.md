---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---
<style>
  h3 {
    border-bottom: 2px solid #1B5E20; /* Accessible Dark Green */
    font-weight: bold;
    padding-bottom: 10px;
    margin-top: 20px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 10px;
    color: #333;
  }

  .media-section {
    margin-top: 20px;
    margin-bottom: 40px;
  }

  .media-card {
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    color: #333333; /* Dark Gray Text */
    box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .media-card:hover {
    transform: translateY(-5px);
    box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.2);
  }

  .media-card:nth-child(odd) {
    background-color: #E3F2FD; /* Light Blue Background */
  }

  .media-card:nth-child(even) {
    background-color: #F3F4F6; /* Light Gray Background */
  }

  .media-card ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .media-card ul li {
    margin-bottom: 15px;
    font-size: 1rem;
  }

  .media-card ul li a {
    color: #1B5E20; /* Dark Green for Links */
    text-decoration: none;
    font-weight: bold;
  }

  .media-card ul li a:hover {
    text-decoration: underline;
  }

  .featured-media {
    background: linear-gradient(45deg, #0056b3, #1A73E8);
    background-size: 400% 400%;
    padding: 30px;
    border-radius: 12px;
    color: #FFFFFF; /* White Text */
    margin-bottom: 40px;
    box-shadow: 0px 8px 25px rgba(0, 0, 0, 0.2);
    animation: gradientShift 6s ease infinite, float 3s ease-in-out infinite;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .featured-media:hover {
    transform: translateY(-5px);
    box-shadow: 0px 8px 25px rgba(0, 0, 0, 0.3);
  }

  @keyframes gradientShift {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  @keyframes float {
    0% {
      transform: translateY(0);
    }
    50% {
      transform: translateY(-10px);
    }
    100% {
      transform: translateY(0);
    }
  }

  .featured-media h3 {
    margin-bottom: 20px;
    font-size: 28px;
    color: #FFEB3B; /* Bright Yellow */
  }

  .tag {
    display: inline-block;
    background: #FFEB3B; /* Bright Yellow Tag Background */
    color: #333; /* Dark Gray Tag Text */
    padding: 4px 8px;
    font-size: 12px;
    border-radius: 4px;
    margin-right: 8px;
    text-transform: uppercase;
    font-weight: bold;
  }

  .tag a {
    color: #333; /* Dark Gray Tag Text */
    text-decoration: none;
  }

  .tag a:hover {
    text-decoration: underline;
  }

  .icon {
    margin-right: 10px;
    color: #FFEB3B; /* Bright Yellow for Icons */
  }
</style>

<!-- Featured Media -->
<div class="featured-media">
  <h3><i class="fas fa-star icon"></i> CAnD3 Fellows Feature</h3>
  <p>
    A highlight of my research as a doctoral fellow at CAnD3, McGill University, 2024.  
    <a href="https://www.mcgill.ca/cand3/article/fellows-feature-mohsen-monji-and-galiba-zahid" target="_blank" style="color: #FFEB3B;">Read more</a>
  </p>
</div>

<!-- Media Cards -->
<div class="media-section">
  <h3><i class="fas fa-newspaper icon"></i> Media Features</h3>

  <!-- Card 1 -->
  <div class="media-card">
    <span class="tag" title="Article feature"><a href="/tag/article/">Article</a></span>
    <ul>
      <li>
        <strong>CAnD3 Fellows Feature: Mohsen Monji</strong> <br>
        <span>McGill University (2024)</span><br>
        A feature article highlighting my research as a doctoral fellow with CAnD3.  
        <a href="https://www.mcgill.ca/cand3/article/fellows-feature-mohsen-monji-and-galiba-zahid" target="_blank">Read more</a>
      </li>
    </ul>
  </div>

  <!-- Card 2 -->
  <div class="media-card">
    <span class="tag" title="Video content"><a href="/tag/video/">Video</a></span>
    <ul>
      <li>
        <strong><i class="fas fa-play-circle" style="margin-right: 8px;"></i>Affecting Machines: Normative Principles for Gender Equity in Artificial Intelligence</strong> <br>
        <span>Concordia University, Fourth Space (2023)</span><br>
        Workshop exploring gender equity in AI.  
        <a href="https://www.youtube.com/watch?v=8aWb-GaUFUI" target="_blank">Watch Video</a>
      </li>
    </ul>
  </div>

  <!-- Card 3 -->
  <div class="media-card">
    <span class="tag" title="Membership"><a href="/tag/membership/">Membership</a></span>
    <ul>
      <li>
        <strong><i class="fas fa-users" style="margin-right: 8px;"></i>Women’s Health Research Cluster Member</strong> <br>
        <span>UBC Women’s Health Research Cluster (2023)</span><br>
        Interdisciplinary research for advancing women’s health.  
        <a href="https://womenshealthresearch.ubc.ca/people/members/?whrc-page-2=30" target="_blank">View Profile</a>
      </li>
    </ul>
  </div>

  <!-- Additional cards omitted for brevity -->
</div>

<!-- Call to Action -->
<div style="text-align: center; margin-top: 50px;">
  <p style="font-size: 18px; color: #333;">
    If you are interested in my work, feel free to <a href="mailto:mohsen.monji@concordia.ca" style="color: #1B5E20;">Get in Touch</a>.
  </p>
</div>



