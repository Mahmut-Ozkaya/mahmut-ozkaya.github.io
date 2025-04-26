---
layout: default
title: Projects
---

<!-- Navbar -->
[Home](./) | [About](./about) | [Projects](./projects)

---

# My Projects

<!-- Animation Styles -->
<style>
.project-container {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin-top: 30px;
}

.project-card {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeSlideIn 0.8s ease forwards;
  background: #f8f8f8;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project-card a {
  text-decoration: none;
  color: #007bff;
  font-weight: bold;
}

.project-card a:hover {
  text-decoration: underline;
}

@keyframes fadeSlideIn {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

[Home](./) | [About](./about) | [Projects](./projects)

---

# My Projects

Here are some of the projects I’ve worked on:

<!-- Project Cards -->
<div class="project-container">

<div class="project-card">
  <h2>Sample Project 1</h2>
  <p>Explanation of Project 1</p>
</div>

<div class="project-card">
  <h2>Sample Project 2</h2>
  <p>Explanation of Project 2</p>
</div>

<div class="project-card">
  <h2>Sample Project 3</h2>
  <p>Explanation of Project 3</p>
</div>

---

More projects coming soon!
