<script setup>
definePageMeta({
  layout: 'with-footer'
})
</script>
<template>
  <section id="hero" class="hero-section">
    <div class="container hero-content">
      <div class="hero-text" data-aos="fade-up">
        <h1 class="text">
          Your Digital Partner<br />
          for Modern
          <span class="it"> IT Solutions</span>
        </h1>
        <p>
          We help business grow through tecnology, strategy, and innovation.
        </p>
      </div>
      <div class="hero-image" data-aos="fade-up">
        <img src="/hero.jpg" alt="Hero Image" />
      </div>
    </div>
  </section>
  <!-- services -->
  <div class="services">
    <div class="container">
      <h1 class="sub-title">Our Services</h1>
      <div class="services-list">
        <div>
          <i class="fas fa-code"></i>
          <h3>Web Devlopment</h3>
          <p>We build scalable and modern website for your business.</p>
          <a href="#">Learn More</a>
        </div>
        <div>
          <i class="fas fa-mobile-alt service-icon"></i>
          <h3>Mobile Apps</h3>
          <p>Cross-platform apps that run smoothly iOS & Android.</p>
          <a href="#">Learn More</a>
        </div>
        <div>
          <i class="fas fa-paint-brush service-icon"></i>
          <h3>UI/UX</h3>
          <p>Beautiful and user-freindly designs that captivate users</p>
          <a href="#">Learn More</a>
        </div>
      </div>
    </div>
  </div>
  </template>

