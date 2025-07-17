<script setup>
definePageMeta({
  layout: 'without-footer'
})
</script>

<template>
  <section class="about-page">
    <!-- About Me Section -->
    <div class="container about-intro">
      <h2 class="section-title">About Us</h2>
      <p class="section-desc">
        At Ruby, we believe in technology with a purpose. Our team is dedicated to crafting tailored solutions that transform businesses and engage users through intuitive design and powerful engineering.
      </p>
    </div>

    <!-- Our Mission -->
    <div class="container about-section mission" data-aos="fade-right">
      <div class="text">
        <h3>Our Mission</h3>
        <p>
          To empower clients with cutting-edge web solutions that elevate their brand and streamline digital interactions. We aim to make technology accessible, intuitive, and impactful.
        </p>
      </div>
      <div class="image">
        <img src="/mission.jpg" alt="Mission Image" />
      </div>
    </div>

    <!-- Our Vision -->
    <div class="container about-section vision" data-aos="fade-left">
      <div class="image">
        <img src="/vision.jpg" alt="Vision Image" />
      </div>
      <div class="text">
        <h3>Our Vision</h3>
        <p>
          To be a leading IT solutions provider recognized for innovation, quality, and trust. We envision a future where digital transformation is seamless and human-centered.
        </p>
      </div>
    </div>

    <!-- Our Values -->
    <div class="container about-section values" data-aos="fade-right">
      <div class="text">
        <h3>Our Values</h3>
        <p>
          Transparency, creativity, and collaboration are at the core of everything we do. We believe in building long-term relationships with our clients through honesty and excellence.
        </p>
      </div>
      <div class="image">
        <img src="/values.jpg" alt="Values Image" />
      </div>
    </div>
  </section>
</template>

<style scoped>
.about-page {
  padding: 80px 20px;
}

.container {
  max-width: 1140px;
  margin: 0 auto;
}

.about-intro {
  text-align: left;
  margin-bottom: 60px;
}

.section-title {
  font-size: 2.8rem;
  font-weight: 700;
  margin-bottom: 20px;
  color: #111;
}

.section-desc {
  font-size: 1.1rem;
  color: #555;
  line-height: 1.7;
  max-width: 700px;
}

.about-section {
  display: flex;
  align-items: center;
  gap: 40px;
  margin-bottom: 80px;
  flex-wrap: wrap;
  background: rgb(186, 160, 160);
  border-radius:10px
}

.about-section .text {
  flex: 1;
  min-width: 280px;
}

.about-section h3 {
  font-size: 2rem;
  margin-bottom: 15px;
  color: #222;
}

.about-section p {
  font-size: 1rem;
  color: #555;
  line-height: 1.6;
}

.about-section .image {
  flex: 1;
  text-align: center;
}

.about-section img {
  width: 100%;
  max-width: 480px;
  border-radius: 10px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}
</style>