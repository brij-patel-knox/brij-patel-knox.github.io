---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Brij Patel's Profile</title>
  
  <!-- Font Awesome CDN for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  
  <!-- CSS Styling -->
  <style>
    /* Basic reset for padding and margin */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body styling */
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f4f4f9;
    }

    /* Main container */
    .profile-container {
      text-align: center;
      padding: 20px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      max-width: 400px;
      width: 100%;
    }

    /* Name styling */
    .profile-name {
      font-size: 24px;
      font-weight: bold;
      color: #333;
    }

    /* Tagline styling */
    .profile-tagline {
      font-size: 18px;
      color: #666;
      margin: 10px 0;
    }

    /* Container for the widgets */
    .widget-container {
      display: flex;
      gap: 20px;
      justify-content: center;
      margin-top: 20px;
    }
    
    /* Styling for each widget icon */
    .widget {
      text-decoration: none;
      color: #333;
      font-size: 36px;
      transition: color 0.3s;
    }
    
    /* Individual hover color styles for each widget */
    .widget.linkedin:hover {
      color: #0077b5; /* LinkedIn blue */
    }
    .widget.github:hover {
      color: #333; /* GitHub black */
    }
    .widget.email:hover {
      color: #d44638; /* Email red */
    }
  </style>
</head>
<body>

  <!-- Profile Container -->
  <div class="profile-container">
    <!-- Name and Tagline -->
    <div class="profile-name">Brij Patel</div>
    <div class="profile-tagline">Computer Science Student | Passionate about Coding and Problem-Solving</div>

    <!-- Social Media Widgets -->
    <div class="widget-container">
      <!-- LinkedIn Widget -->
      <a href="https://www.linkedin.com/in/your-profile" target="_blank" class="widget linkedin" title="LinkedIn">
        <i class="fab fa-linkedin"></i>
      </a>
      
      <!-- GitHub Widget -->
      <a href="https://github.com/your-username" target="_blank" class="widget github" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
      
      <!-- Email Widget -->
      <a href="mailto:your-email@example.com" class="widget email" title="Email">
        <i class="fas fa-envelope"></i>
      </a>
    </div>
  </div>

</body>
</html>
