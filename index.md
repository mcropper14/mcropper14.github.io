---
layout: default
title: Home
---

<style>
body {
  background: #111;
  color: #00ff00;
  font-family: 'Fira Mono', 'Consolas', monospace;
}
a { color: #00ff00; }
.nav {
  margin: 2em 0;
  display: flex;
  gap: 2em;
  font-size: 1.2em;
}
.header {
  display: flex;
  align-items: center;
  gap: 2em;
}
.autonomous-theme {
  margin-top: 2em;
  padding: 1em;
  border: 2px dashed #00ff00;
  border-radius: 10px;
  background: rgba(0,255,0,0.05);
  text-align: center;
  position: relative;
  overflow: hidden;
}

.car-animation {
  position: relative;
  height: 60px;
  margin: 1em 0;
}

.car {
  position: absolute;
  left: -100px;
  animation: drive 4s linear infinite;
  width: 80px;
  height: 30px;
}

.road {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 4px;
  background: #00ff00;
  opacity: 0.3;
}

@keyframes drive {
  0% { left: -100px; }
  100% { left: 100%; }
}

.car svg {
  width: 100%;
  height: 100%;
}
img.profile {
  border-radius: 50%;
  border: 3px solid #00ff00;
  width: 180px;
  background: #222;
}
</style>

<div class="header">
  <img src="/photos/photo-removebg-preview.png" alt="Profile photo"/>
  <div>
    <h1>Hello World, I'm Myra</h1>
    <h2>I just finished ugrad in CS. I'm an incoming ECE MS Student @ Carnegie Mellon University</h2>
    <h2>I'm interested in autonomous driving, robotics, and AI/ML. Looking for summer 2026 internship and FT Decemeber 2026.</h2>
    <p>Contact me @myracropper32@gmail.com</p>
    
  </div>
</div>

<nav class="nav">
  <a href="/resume/">Resume</a>
  <a href="/projects/">Projects</a>
  <a href="/frameworks/">Frameworks</a>
  <a href="/thoughts/">Thoughts</a>
  <a href="/books/">Book Recommendations</a>
</nav>

<div class="autonomous-theme">
  <div class="car-animation">
    <div class="road"></div>
    <div class="car">
      <svg viewBox="0 0 100 40">
        <!-- Car body -->
        <rect x="15" y="15" width="70" height="20" rx="5" fill="#00ff00" opacity="0.8"/>
        <!-- Car roof -->
        <rect x="35" y="5" width="30" height="15" rx="3" fill="#00ff00" opacity="0.6"/>
        <!-- Wheels -->
        <circle cx="25" cy="35" r="8" fill="#00ff00"/>
        <circle cx="75" cy="35" r="8" fill="#00ff00"/>
        <!-- Headlights -->
        <circle cx="85" cy="20" r="3" fill="#00ff00" opacity="0.9"/>
        <!-- Taillights -->
        <circle cx="15" cy="20" r="2" fill="#ff0000" opacity="0.7"/>
      </svg>
    </div>
  </div>
  <p>Cars go vroom.</p>
</div> 