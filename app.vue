<template>
  <div class="cv-container">
    <div class="header">
      <h1>Pradipta Rahmatan Isya Hertanto</h1>
      <p>Student at Brawijaya University</p>
    </div>
    
    <div class="content">
      <section class="about">
        <h2>About Me</h2>
        <p>Nama saya Pradipta Rahmatan Isya Hertanto, seorang mahasiswa D3 Teknologi Informasi di Universitas Brawijaya, Fakultas Vokasi. Sejak kecil, saya selalu tertarik pada dunia teknologi, yang mendorong saya untuk memilih jurusan ini. Selain belajar tentang teknologi dan informasi, saya juga memiliki hobi yang mengisi waktu luang saya, yaitu bermain alat musik dan mendengarkan berbagai genre musik. Musik adalah salah satu cara saya untuk mengekspresikan diri dan menemukan inspirasi. Dengan latar belakang di bidang teknologi dan ketertarikan yang mendalam terhadap musik, saya berharap dapat menggabungkan kedua passion ini di masa depan, baik dalam proyek-proyek teknologi maupun dalam kolaborasi kreatif lainnya.</p>
      </section>
      
      <section class="education">
        <h2>Education</h2>
        <ul>
          <li>
            <h3>Universitas Brawijaya</h3>
            <p>Sedang Berkuliah di Universitas Brawijaya, Prodi Teknologi Informasi [D3] (2023 - Sekarang)</p>
          </li>
        </ul>
      </section>
      
      <section class="skills">
        <h2>Skills</h2>
        <ul>
          <li>Web Development</li>
          <li>JavaScript & Vue.js</li>
          <li>HTML & CSS</li>
        </ul>
      </section>
      
      <section class="contact">
  <h2>Contact</h2>
  <ul>
    <li>
      <a href="mailto:diptabeldoz40@gmail.com" class="contact-item">
        <img src="https://w7.pngwing.com/pngs/333/868/png-transparent-mail-computer-icons-email-graphy-e-mail-miscellaneous-angle-rectangle-thumbnail.png" alt="Email Icon" class="icon" />
        diptabeldoz40@gmail.com
      </a>
    </li>
    <li>
      <a href="https://instagram.com/praadiptaa" target="_blank" class="contact-item">
        <img src="https://static.vecteezy.com/system/resources/previews/023/986/891/original/instagram-logo-instagram-logo-transparent-instagram-icon-transparent-free-free-png.png" alt="Instagram Icon" class="icon" />
        Instagram: @praadiptaa
      </a>
    </li>
    <li>
      <a href="https://wa.me/+6281456183898" class="contact-item" target="_blank">
        <img src="https://toppng.com/uploads/preview/whatsapp-logo-symbol-vector-free-11574065504yglrgcmcmx.png" alt="WhatsApp Icon" class="icon" />
        WhatsApp: +6281456183898
      </a>
    </li>
  </ul>
</section>

    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
.cv-container {
  font-family: 'Garamond', serif;
  background-color: #FAF3E0;
  color: #5D4037;
  padding: 20px;
  max-width: 1600px;
  width: 95%;
  margin: 0 auto;
  border: 1px solid #D7CCC8;
  border-radius: 10px;
  box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.1);
}

.header {
  text-align: center;
  padding: 20px 0;
}

h1 {
  font-size: 3rem;
  color: #4E342E;
}

h2 {
  font-size: 2rem;
  border-bottom: 2px solid #8D6E63;
  padding-bottom: 5px;
}
h3 {
  font-size: 2rem;
  border-bottom: 2px solid #8D6E63;
  padding-bottom: 5px;
}
p {
  font-size: 1.2rem;
  line-height: 1.6;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  padding: 5px 0;
}

.content {
  margin-top: 20px;
}

section {
  margin-bottom: 20px;
  padding: 10px;
  border-left: 4px solid #A1887F;
  background-color: #ECE2D0;
  border-radius: 5px;
  transition: background-color 0.3s;
}

section:hover {
  background-color: #E0BFB8;
}

.contact-item {
  display: flex;
  align-items: center;
  text-decoration: none;
  color: #5D4037;
}

.contact-item:hover {
  color: #4E342E;
}

.icon {
  width: 20px;
  height: 20px;
  margin-right: 10px;
}

/* Media queries for responsiveness */
@media (min-width: 1800px) {
  .cv-container {
    max-width: 1800px;
  }
}
</style>
