---
layout: home
title: Home
permalink: /
---

<style>
/* Hero section */
.hero {
  background: url('/assets/images/hero.jpg') center/cover no-repeat;
  height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  color: white;
  text-align: center;
}

.hero::after {
  content: '';
  position: absolute;
  inset: 0;
  background-color: rgba(0, 0, 0, 0.5); /* semi-transparent overlay */
}

.hero-content {
  position: relative;
  z-index: 1;
  max-width: 700px;
  margin: 0 auto;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.section {
  padding: 60px 20px;
  max-width: 1200px;
  margin: auto;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.section img {
  width: 30%;
  margin: 10px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

.section .link {
  display: block;
  margin-top: 20px;
  font-weight: bold;
  text-decoration: underline;
  color: #9147ff;
}
</style>

<!-- Hero Section -->
<div class="hero">
  <div class="hero-content">
    <h1>Welcome to GameScope</h1>
    <p>Discover the latest news and honest reviews of trending games.</p>
  </div>
</div>

<!-- Latest Game News Section -->
<div class="section" id="news">
  <h2>Latest Game News</h2>
  <div>
    <img src="/assets/images/news1.jpg" alt="Game News 1">
    <img src="/assets/images/news2.jpg" alt="Game News 2">
    <img src="/assets/images/news3.jpg" alt="Game News 3">
  </div>
  <a href="/game-news/" class="link">Read More Game News →</a>
</div>

<!-- Game Reviews Section -->
<div class="section" id="reviews">
  <h2>Game Reviews</h2>
  <div>
    <img src="/assets/images/review1.jpg" alt="Review 1">
    <img src="/assets/images/review2.jpg" alt="Review 2">
    <img src="/assets/images/review3.jpg" alt="Review 3">
  </div>
  <a href="/games/" class="link">Explore All Reviews →</a>
</div>
