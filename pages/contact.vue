<script setup>
definePageMeta({
  layout: 'without-footer'
})
</script>
<template>
  <div class="page-body">
    <section class="contact-section">
      <div class="container">
        <h2 class="section-title">Get in Touch with Ruby</h2>
        <p>We would love to hear from you! Whether you have a question about our services, need support, or want to discuss a project, feel free to reach out.</p>
        <div class="contact-box">
          <form class="contact-form">
            <div class="form-group">
              <input type="text" placeholder="Your Name" required />
            </div>
            <div class="form-group">
              <input type="email" placeholder="Your Email" required />
            </div>
            <div class="form-group">
              <textarea placeholder="Your Message" rows="5" required></textarea>
            </div>
            <button type="submit">Send Message</button>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>


<style scoped>

.contact-section {
  padding: 100px 0;
  background: #f8f9fa;
  text-align: center;
}

.section-title {
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 40px;
  color: #222;
}

.contact-box {
  max-width: 600px;
  margin: 0 auto;
  background: white;
  padding: 40px;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
}

.contact-form .form-group {
  margin-bottom: 20px;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 14px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 1rem;
}

.contact-form button {
  background-color: #007bff;
  color: white;
  border: none;
  padding: 12px 24px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 1rem;
  transition: background 0.3s;
}

.contact-form button:hover {
  background-color: #0056b3;

}
.section-title {
  margin-bottom: 10px; 
}

.container p {
  margin-top: 0;
  margin-bottom: 20px; 
}
</style>
