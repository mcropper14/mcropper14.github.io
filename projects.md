---
layout: default
title: Projects
---

<style>
body { background: #111; color: #00ff00; font-family: 'Fira Mono', 'Consolas', monospace; }
h2 { color: #00ff00; border-bottom: 1px solid #00ff00; }
.project { margin-bottom: 2em; background: #222; padding: 1em; border-radius: 10px; }
.tech { font-size: 0.95em; color: #0f0; }
.links { margin-top: 1em; }
.links a { 
  color: #00ff00; 
  text-decoration: underline; 
  margin-right: 1em; 
  font-size: 0.9em;
}
.links a:hover { 
  color: #0f0; 
  text-decoration: none; 
}
</style>

<h1>Autonomous Driving/Relevant Projects</h1>
<h1>More experience and general projects are listed in my resume</h1>


<div class="project">
  <h2>Adaptive Multi-Camera Sensor Fusion</h2>
  <p>Developed a multi-sensor perception framework integrating Multi-Head Latent Attention (MLA) and LSTM networks to fuse Vision Transformer features from multi-camera inputs for autonomous driving.</p>
  <div class="tech">Frameworks: PyTorch, ROS2 GNSS, Python</div>
  <div class="links">
    <a href="https://github.com/mcropper14/Multi-Camera-Fusion" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
  </div>
</div>

<div class="project">
  <h2>Autonomous Vehicle Honors Thesis</h2>
  <p>Built an EfficientNet-LSTM pipeline achieving 92% lane detection accuracy, implemented YOLO-based object tracking, and created 3D visualizations of environments using RVIZ. Enabled V2V robot communication via DDS.</p>
  <div class="tech">Frameworks: TensorFlow, YOLO, ROS2, RVIZ, Python</div>
  <div class="links">
    <a href="https://github.com/mcropper14/Thesis-Code" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
    <a href="https://scholarworks.wm.edu/items/45526fa7-9760-4d64-98bb-5d7508051262" target="_blank" rel="noopener noreferrer">Paper</a>
    <a href="https://youtu.be/s9K2VZNC5XY?si=qbP3FQQOfu6W5Ium" target="_blank" rel="noopener noreferrer">Demo</a>
  </div>
</div>

<div class="project">
  <h2>Comma.ai Calibration Challenge</h2>
  <p>Developed a Kalman Filter-based lane detection system for comma.ai's calibration challenge, achieving MSE of <25% on test data. Implemented curved lane detection, pitch/yaw calculation from vanishing points, speed estimation via optical flow, and parallelism enforcement for consistent lane tracking.</p>
  <div class="tech">Frameworks: Python, OpenCV, NumPy, Kalman Filters</div>
  <div class="links">
    <a href="https://github.com/mcropper14/commaai_calib_code" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
    <a href="https://youtube.com/shorts/EXIoAvla1Tc?feature=share" target="_blank" rel="noopener noreferrer">Video Demo</a>
    <a href="https://github.com/commaai/calib_challenge" target="_blank" rel="noopener noreferrer">Challenge Link</a>
  </div>
</div>

<h1>Some hackathon projects</h1>

<div class="project">
  <h2>Homeview - VTHacks 2024</h2>
  <p>Developed an LLM + RAG fullstack application for homebuying that achieved higher accuracy than traditional LLMs. Built with authentication and deployed as a web platform to help users make informed real estate decisions.</p>
  <div class="tech">Frameworks: React, Node.js, LLM, RAG, Authentication</div>
  <div class="links">
    <a href="https://devpost.com/software/homeview" target="_blank" rel="noopener noreferrer">Devpost</a>
    <a href="https://github.com/F4llow/Homeview" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
  </div>
</div>

<div class="project">
  <h2>Trayce - Smart Waste-Sorting Assistant</h2>
  <p>Developed a computer vision-powered waste-sorting assistant that uses Google Gemini 2.0 Vision API and YOLOv11 to identify and classify food tray items into trash, recycle, compost, or dish return. Features include real-time object detection with bounding boxes, USDA food database integration for nutritional insights, and Auth0 authentication with SQLite for tracking user sustainability impact.</p>
  <div class="tech">Frameworks: React, TypeScript, Flask, Python, Gemini API, YOLOv11, SQLite, Auth0, Tailwind CSS</div>
  <div class="links">
    <a href="https://github.com/F4llow/trayce" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
    <a href="https://devpost.com/software/trayce" target="_blank" rel="noopener noreferrer">Devpost</a>
  </div>
</div>

<div class="project">
  <h2>CapitalSavy - Credit Card Fraud Detection</h2>
  <p>Developed a machine learning model using deep neural networks to identify credit card fraud with 99.5% accuracy. Built a full-stack web application with TensorFlow backend and intuitive frontend interface. Implemented dropout layers and K-Fold validation to prevent overfitting, analyzing over 550,000 anonymized European credit card transactions from 2023. Won best Finance Hack.</p>
  <div class="tech">Frameworks: Python, TensorFlow, Deep Neural Networks, VPS, Full-stack Web Development</div>
  <div class="links">
    <a href="https://github.com/F4llow/FraudAI" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
    
  </div>
</div>

<div class="project">
  <h2>Griffin Events - AI-Powered Event Discovery</h2>
  <p>Built an AI-powered event discovery platform for William & Mary using LLM + RAG (Retrieval Augmented Generation) with a self-hosted Mixtral 7B model. Aggregated event data from multiple campus sources (TribeLink, official W&M sites, department mailing lists, etc.) and created a vector database for efficient retrieval. Features include natural language event queries, geographical filtering, and secure authentication with PropelAuth. Won Best Accessibility & Belonging Hack at &hacks 10.</p>
  <div class="tech">Frameworks: Python, Node.js, LLM, RAG, Mixtral 7B, Vector Database, PropelAuth, AlmaLinux VPS</div>
  <div class="links">
    <a href="https://devpost.com/software/andhacks-project" target="_blank" rel="noopener noreferrer">Devpost</a>
  </div>
</div>

<h1>Outside of these projects and school, I enjoy working on cars.</h1>

I use Toyota Techstream software for reprogramming software in my car and running diagonistics. 
<div class="links">
    <a href="https://youtu.be/-Sa1HQ34xig" target="_blank" rel="noopener noreferrer">More info</a>
    
  </div>



I'm currently working on reprogramming an vehicle cluster. 

Here's some pictures as well of one of the better go-karts I've built with my friends.

<div class="project">
  <h2>Go-Kart Project</h2>
  <p>Built a custom go-kart with friends, showcasing hands-on mechanical and engineering skills.</p>
  
  <!-- Add your go-kart pictures here -->


<img src="/photos/gochart2.jpg" alt="Go-kart project - side view" />
  <p class="image-caption">Front view</p>

  <img src="/photos/gocart1.jpg" alt="Go-kart project - front view" />
  <p class="image-caption">Back View with my friend welding.</p>
  
  
  
</div> 
