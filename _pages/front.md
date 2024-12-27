<style>
  /* Container for the animated text */
  .animated-text-container {
    display: inline-block;
    text-align: center;
    overflow: hidden;
    white-space: nowrap;
    border-right: 2px solid #007bff;
    font-size: 18px;
    font-weight: normal;
    color: #333;
    animation: typing 8s steps(60, end), blink 0.5s step-end infinite;
  }

  /* Typing effect */
  @keyframes typing {
    from {
      width: 0;
    }
    to {
      width: 100%;
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

  <!-- Animated Description -->
  <div style="max-width: 700px; margin: 0 auto; line-height: 1.8;">
    <div class="animated-text-container">
      I am a <strong>PhD Candidate in Sociology</strong> at Concordia University, a <strong>CAnD3 Doctoral Fellow</strong> at McGill University, and a <strong>CRDCN Emerging Scholar</strong>. My research focuses on <strong>social determinants of mental health</strong> and disparities in outcomes among <strong>youth</strong> and <strong>young adults</strong>.
    </div>
  </div>
  
  <!-- Buttons -->
  <div style="margin-top: 20px;">
    <a href="/about-me/" style="display: inline-block; padding: 10px 20px; background-color: #007BFF; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin-bottom: 10px;">Learn More About Me</a><br>
    <a href="/curriculum/" style="display: inline-block; padding: 10px 20px; background-color: #28A745; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">View My CV</a>
  </div>
</div>
