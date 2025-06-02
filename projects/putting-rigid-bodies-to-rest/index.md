---
layout: page
title: "Projects"
permalink: /projects/
---

<style>
/* Simple grid for project cards */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  grid-gap: 2rem;
  margin-top: 2rem;
}
.project-card {
  border: 1px solid #e1e1e1;
  border-radius: 8px;
  overflow: hidden;
  transition: box-shadow .2s ease;
}
.project-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,.1);
}
.project-card img {
  width: 100%;
  height: auto;
  display: block;
}
.project-card-content {
  padding: 1rem;
}
.project-card-content h2 {
  margin-top: 0;
  font-size: 1.25rem;
}
.project-card-content p {
  margin: .5rem 0 1rem;
  color: #555;
}
.project-card-content a.button {
  display: inline-block;
  padding: .5rem 1rem;
  background: #007acc;
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
}
.project-card-content a.button:hover {
  background: #005fa3;
}
</style>

# My Research Projects

Below is a selection of my recent work. Click on each card to learn more:

<div class="projects-grid">

  <div class="project-card">
    <a href="/projects/putting-rigid-bodies-to-rest/">
      <img src="/images/putting-rigid-bodies/cover.png" alt="Cover: Putting Rigid Bodies to Rest">
    </a>
    <div class="project-card-content">
      <h2><a href="/projects/putting-rigid-bodies-to-rest/">Putting Rigid Bodies to Rest</a></h2>
      <p><em>H. Baktash et al.</em> A study of equilibrium distributions of rolling rigid bodies under drag forces.</p>
      <a class="button" href="/projects/putting-rigid-bodies-to-rest/">Learn More</a>
    </div>
  </div>

  <!--
  Copy this block to add more projects.
  Just update the image, link, title, authors, and blurb.
  -->
  <!--
  <div class="project-card">
    <a href="/projects/another-project/">
      <img src="/images/another-project/cover.png" alt="Cover: Another Project">
    </a>
    <div class="project-card-content">
      <h2><a href="/projects/another-project/">Another Project Title</a></h2>
      <p><em>Your Name et al.</em> One‐sentence description of what this project does.</p>
      <a class="button" href="/projects/another-project/">Learn More</a>
    </div>
  </div>
  -->

</div>
