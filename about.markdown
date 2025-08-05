---
layout: default
title: About
permalink: /about/
---

<!-- Banner Section -->
<div class="about-banner">
  <img src="/assets/images/about.jpg" alt="Banner" />
  <h1>About</h1>
</div>

<!-- Content Section -->
<div class="about-container">
  <div class="about-img">
    <img src="/assets/images/aboutme.jpg" alt="Me as a kid" />
  </div>
  <div class="about-text">
    <h2>Who Am I?</h2>
    <p>
      I am a passionate member of the game industry and an indie developer. Ever since I was a child, games have been a part of my life. With decades of gaming experience, I offer a unique and insightful perspective on what games can be and should be.
    </p>

    <h2>Why This Website?</h2>
    <p>
      I created this platform to encourage open, respectful dialogue among gamers. Here, all voices are welcome—whether praise or critique. Through honest discussions and shared perspectives, we can contribute to a healthier, more creative gaming industry.
    </p>
  </div>
</div>

<style>
  .about-banner {
    position: relative;
    height: 300px;
    overflow: hidden;
  }
  .about-banner img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter: brightness(50%);
  }
  .about-banner h1 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 3rem;
    margin: 0;
  }
  .about-container {
    max-width: 1000px;
    margin: 2rem auto;
    padding: 0 1rem;
    display: flex;
    gap: 2rem;
    align-items: flex-start;
  }
  .about-img img {
    width: 300px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  }
  .about-text h2 {
    margin-top: 0;
  }
  .about-text p {
    line-height: 1.6;
  }
</style>
