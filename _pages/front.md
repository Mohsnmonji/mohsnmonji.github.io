<style>
  /* Style for futuristic fade-in text animation */
  .animated-description {
    opacity: 0;
    color: #00bfff; /* Futuristic neon blue */
    text-shadow: 0 0 5px #00bfff, 0 0 10px #00bfff;
    font-size: 18px;
    animation: fadeIn 3s ease-in-out forwards; /* Fade in over 3 seconds */
  }

  /* Keyframes for fade-in animation */
  @keyframes fadeIn {
    0% {
      opacity: 0;
      transform: translateY(10px); /* Slight upward motion */
    }
    100% {
      opacity: 1;
      transform: translateY(0); /* Settles into place */
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
  <p class="animated-description">
    I am a sociologist and population mental health researcher studying the <strong>social determinants of mental health</strong> 
    and <strong>mental health disparities</strong> among <strong>youth</strong> and <strong>young adults</strong> in Canada and the US.
  </p>
  
  <!-- Buttons -->
  <div style="margin-top: 20px;">
    <a href="/about-me/" style="display: inline-block; padding: 10px 20px; background-color: #007BFF; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin-bottom: 10px;">Learn More About Me</a><br>
    <a href="/curriculum/" style="display: inline-block; padding: 10px 20px; background-color: #28A745; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">View My CV</a>
  </div>
</div>
