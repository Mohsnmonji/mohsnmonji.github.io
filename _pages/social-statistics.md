---
layout: archive
permalink: /social-statistics/
title: "Social Statistics"
author_profile: true
---

<style>
  /* General Styling for Blog Archive */
  .blog-section {
    margin-top: 30px;
  }

  .blog-title {
    border-bottom: 2px solid #1B5E20; /* Accessible Dark Green */
    font-weight: bold;
    padding-bottom: 10px;
    margin-bottom: 20px;
    color: #333; /* Dark Gray for Heading Text */
  }

  .post-cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px; /* Spacing between cards */
    margin-top: 20px;
    justify-content: space-around; /* Center the cards */
  }

  .post-card {
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
    background-color: #E3F2FD; /* Light Blue Background */
    box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1); /* Subtle Shadow */
    text-align: justify; /* Justify text within cards */
    width: 100%; /* Full width for smaller screens */
    max-width: 300px; /* Limit width of each card */
    flex: 1 1 300px; /* Responsive layout */
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .post-card:hover {
    transform: translateY(-5px); /* Slight lift effect on hover */
    box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.2); /* Enhanced shadow on hover */
  }

  .post-card h3 {
    font-weight: bold;
    margin-bottom: 10px;
    color: #1B5E20; /* Accessible Dark Green for titles */
  }

  .post-card p {
    margin: 0;
    color: #555; /* Medium Gray for text */
    font-size: 1rem;
    line-height: 1.5;
  }

  .post-card a {
    display: inline-block;
    margin-top: 10px;
    color: #1B5E20; /* Accessible Dark Green for links */
    text-decoration: none;
    font-weight: bold;
  }

  .post-card a:hover {
    text-decoration: underline;
  }

  /* Removed Badge Styling */
</style>

<div class="blog-section">
  <h2 class="blog-title">TOPICS</h2>
  <div class="post-cards">
    {% for post in site.posts %}
    <div class="post-card">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
      <p class="post-categories">Categories: {{ post.categories | join: ', ' }}</p>
      <a href="{{ post.url | relative_url }}">Read More</a>
    </div>
    {% endfor %}
  </div>
</div>
