<script setup>
definePageMeta({
  layout: 'without-footer'
})

const services = [
  {
    image: '/web.jpg',
    title: 'Web Development',
    desc: 'We craft responsive, high-performance websites that blend modern design with robust functionality. From business sites to custom platforms, we ensure your online presence is fast, secure, and impactful.'
  },
  {
 image: '/app.jpg',
    title: 'App Development',
    desc: 'We build powerful mobile and web applications tailored to your needs — scalable, user-friendly, and ready for real-world impact. Whether Android, iOS, or cross-platform, we turn your vision into seamless experiences.'
  },
  {image:'/ui.png',
  title:'UI/UX design',
  desc: 'We create intuitive and visually striking interfaces focused on user experience. From wireframes to polished designs, our goal is to ensure every interaction feels effortless, meaningful, and brand-aligned.'
}
]
</script>

<template>
  <section class="service-section" >
    <div class="container">
      <div
        v-for="(service, index) in services"
        :key="index"
        class="service-box mb-5"
        :class="{ reverse: index % 2 !== 0 }"
      >
        <img :src="service.image" alt="service" class="service-image" />
        <div class="service-text">
          <h3 class="service-title">{{ service.title }}</h3>
          <p class="service-desc">{{ service.desc }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.service-section {
  padding: 60px 0;
  background-color: #f9f9f9;
}

.service-box {
  display: flex;
  align-items: center;
  gap: 30px;
  flex-wrap: wrap;
  background: rgb(186, 160, 160);
  border-radius:10px;
}

.service-box.reverse {
  flex-direction: row-reverse;
}

.service-image {
  width: 500px;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.service-text {
  text-align: left;
  max-width: 600px;
}
</style>