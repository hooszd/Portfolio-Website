<template>
   <Navber />
   <section id="hero">
    <div class="hero container">
      <div>
        <h1>Hello, <span></span></h1>
        <h1>My Name is <span></span></h1>
        <h1>Kanokwan  Doungkeaw <span></span></h1>
        <a href="#projects" type="button" class="cta">My Profile</a>
      </div>
    </div>
  </section>
  <!-- End Hero Section  -->

  <!-- Service Section -->
  <section id="services">
    <div class="services container">
      <div class="service-top">
        <h1 class="section-title">Kano<span>K</span>wan</h1>
        <p>In three words I can sum up everything I’ve learned about life : it goes on.</p>
      </div>
      <div class="service-item">
        <h2>My experiencers</h2>
        <p>แข่งตอบปัญหา , แข่งกล่าวสุนทรพจน์ , Python Programming , ต่อวงจรไฟฟ้า</p>
      </div>
    </div>
  </section>
  <!-- End Service Section -->

  <!-- Projects Section -->
  <section id="projects">
    <div class="projects container">
      <div class="projects-header">
        <h1 class="section-title">Recent <span>Projects</span></h1>
      </div>
      <div class="all-projects">
        <div class="project-item">
          <div class="project-info">
            <h1>Cup sleeves</h1>
            <h2>2020</h2>
            <p>"ออกแบบคัพสลิปของโปรเจคคาเฟ่วันเกิดคิมฮันบิน"</p>
          </div>
          <div class="project-img">
            <img src="./pj.jpg" alt="img">
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Projects Section -->

  <!-- About Section -->
  <section id="about">
    <div class="about container">
      <div class="col-left">
        <div class="about-img">
          <img src="./pf.jpg" alt="img">
        </div>
      </div>
      <div class="col-right">
        <h1 class="section-title">About <span>me</span></h1>
        <h2>Be You. Do You. For You.</h2>
        <p>Six years of high school, science-mathematics, learning python programming, circuit connection, resulting in an interest in technology, Programming and choose to study in the field of technology.</p>
      </div>
    </div>
  </section>
  <!-- End About Section -->

  <!-- Contact Section -->
  <section id="contact">
    <div class="contact container">
      <div>
        <h1 class="section-title">Contact <span>info</span></h1>
      </div>
      <div class="contact-items">
        <div class="contact-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/new-post.png" /></div>
          <div class="contact-info">
            <h1>Email</h1>
            <h2>kanokwan.doun@bumail.net</h2>
          </div>
        </div>
        <div class="contact-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/map-marker.png" /></div>
          <div class="contact-info">
            <h1>Location</h1>
            <h2>Thailand</h2>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Contact Section -->

  <!-- Footer -->
  <section id="footer">
    <div class="footer container">
      <div class="brand">
        <h1><span>K</span>anokwan <span>D</span>oungkeaw</h1>
      </div>
      <h2>Your Complete Web Solution</h2>
      <div class="social-icon">
        <div class="social-item">
          <a href="#"><img src="https://img.icons8.com/bubbles/100/000000/instagram-new.png" /></a>
        </div>
      </div>
      <p>© 2020 Kanokwan  Doungkeaw</p>
    </div>
  </section>
</template>

<script>
import Navbar from '../components/Navber.vue';
export default {
    companents: { Navbar }
}
</script>

<style>

</style>