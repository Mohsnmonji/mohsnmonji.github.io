<style>
  /* Style for the word-by-word animation */
  .animated-text {
    display: inline-block;
    overflow: hidden;
    white-space: nowrap;
    border-right: 2px solid #007bff;
    animation: typing 8s steps(80, end), blink 0.5s step-end infinite;
    font-size: 18px;
    max-width: 100%; /* Ensure responsive text wrapping */
  }

  /* Typing animation for multiple lines */
  .animated-text-wrapper {
    display: inline-block;
    white-space: normal;
    overflow: hidden;
    border-right: 2px solid #007bff;
    animation: typing-multiline 8s steps(80, end), blink 0.5s step-end infinite;
  }

  @keyframes typing-multiline {
    from {
      max-height: 0;
    }
    to {
      max-height: 100%;
    }
  }

  /* Blinking cursor */
  @keyframes blink {
    from,
    to {
      border-color: transparent;
    }
    50% {
      border-color: #007bff;
    }
  }
</style>

<div style="text-align: center; margin-top: 50px;">
  <!-- Profile Image -->
  <img src="images/profile.PNG" alt="Profile Picture of Mohsen Monji" style="max-width: 300px; height: auto; border-radius: 50%; margin-bottom: 20px; box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);">
  
  <!-- Name -->
  <h1 style="color: #333; margin-bottom: 5px;">MOHSEN MONJI</h1>
  
  <!-- Subtitle -->
  <p style="font-style: italic; font-size: 18px; margin-top: 5px; color: #555;">
    PhD Candidate in Sociology & Lecturer, FRQSC Doctoral Scholar, CAnD3 Doctoral Fellow, CRDCN Emerging Scholar
  </p>
 
  <!-- Animated Multiline Description -->
  <p style="max-width: 700px; margin: 0 auto; color: #333; text-align: justify; line-height: 1.8;">
    <span class="animated-text-wrapper">
      I am a <strong>PhD Candidate in Sociology</strong> at <a href="https://www.concordia.ca/artsci/sociology-anthropology.html" target="_blank">Concordia University</a>, 
      a <strong>CAnD3 Doctoral Fellow</strong> at <a href="https://www.mcgill.ca/cand3/our-people/fellows-2024-25" target="_blank">McGill University</a>, 
      and a <strong>CRDCN Emerging Scholar</strong> at the <a href="https://crdcn.ca" target="_blank">Canadian Research Data Centre Network (CRDCN)</a>. 
      My doctoral research is focused on the <strong>social determinants of mental health</strong> and population-level disparities in mental health outcomes, 
      particularly <strong>psychological distress</strong>, <strong>anxiety</strong>, and <strong>depression</strong> among <strong>youth</strong> and <strong>young adults</strong> in Canada.
    </span>
  </p>
  
  <!-- Buttons -->
  <div style="margin-top: 20px;">
    <a href="/about-me/" style="display: inline-block; padding: 10px 20px; background-color: #007BFF; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin-bottom: 10px;">Learn More About Me</a><br>
    <a href="/curriculum/" style="display: inline-block; padding: 10px 20px; background-color: #28A745; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">View My CV</a>
  </div>
</div>
