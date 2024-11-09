---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Brij Patel
Computer Science Student | Passionate about Coding and Problem-Solving
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Social Media Widgets</title>
  
  <!-- Font Awesome CDN for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  
  <!-- CSS Styling for the widget container and individual widgets -->
  <style>
    /* Container for all widgets */
    .widget-container {
      display: flex;
      gap: 20px;
      justify-content: center;
      margin-top: 50px;
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

  <!-- Container for LinkedIn, GitHub, and Email widgets -->
  <div class="widget-container">
    <!-- LinkedIn Widget -->
    <a href="https://www.linkedin.com/in/brij-patel-a291052b4/" target="_blank" class="widget linkedin" title="LinkedIn">
      <i class="fab fa-linkedin"></i>
    </a>
    
    <!-- GitHub Widget -->
    <a href="https://github.com/brij-patel-knox" target="_blank" class="widget github" title="GitHub">
      <i class="fab fa-github"></i>
    </a>
    
    <!-- Email Widget -->
    <a href="mailto:bpatel@knox.edu" class="widget email" title="Email">
      <i class="fas fa-envelope"></i>
    </a>
  </div>

</body>
</html>

