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
    <h1>Hi, I'm Myra</h1>
    <h2>I just finished ugrad in CS from William & Mary. I'm an incoming ECE MS Student at Carnegie Mellon University</h2>
    <p>I have some of my projects and resume on here.</p>
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
  <svg width="100" height="40" viewBox="0 0 100 40">
    <rect x="10" y="20" width="80" height="10" rx="5" fill="#00ff00" opacity="0.2"/>
    <circle cx="25" cy="35" r="5" fill="#00ff00"/>
    <circle cx="75" cy="35" r="5" fill="#00ff00"/>
    <rect x="40" y="10" width="20" height="10" rx="3" fill="#00ff00" opacity="0.2"/>
  </svg>
  <p>Cars go vroom.</p>
</div> 