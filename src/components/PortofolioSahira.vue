<template>
  <div class="portfolio-wrapper">
    <div class="portfolio-container">
      <h1>🌸 Portofolio Sahira Ayiska</h1>

      <section>
        <h2>🧕 Tentang Saya</h2>
        <p>
          Halo! Saya <strong>Sahira Ayiska</strong>, lahir pada <strong>16 Februari 2005</strong>.
          Saat ini saya adalah mahasiswi <strong>Teknik Informatika</strong> di <strong>Universitas Islam Riau</strong>.
          Saya memiliki minat besar dalam bidang teknologi, khususnya pemrograman dan pengembangan aplikasi.
        </p>
      </section>

      <section>
        <h2>🎓 Riwayat Pendidikan</h2>
        <ul>
          <li><span>SD:</span> SDS Hubbulwathan</li>
          <li><span>SMP:</span> SMPS Hubbulwathan</li>
          <li><span>SMK:</span> SMKN 1 Mandau (Teknik Komputer dan Jaringan)</li>
          <li><span>Perguruan Tinggi:</span> Universitas Islam Riau (Teknik Informatika)</li>
        </ul>
      </section>

      <section>
        <h2>💼 Pengalaman & Kegiatan</h2>
        <ul>
          <li>Magang di Dinas Tenaga Kerja dan Transmigrasi – bidang jaringan & administrasi teknis.</li>
          <li>Anggota MPK saat SMP – aktif dalam organisasi dan komunikasi publik.</li>
        </ul>
      </section>

      <section>
        <h2>🛠️ Keahlian</h2>
        <ul>
          <li>Mampu bekerja sama dalam tim secara efektif</li>
          <li>Memiliki keterampilan komunikasi yang baik</li>
          <li>Berorientasi pada solusi dan cepat belajar hal baru</li>
          <li>Adaptif, fleksibel, dan mampu menghadapi tantangan</li>
          <li>Memiliki semangat belajar dan berkembang secara berkelanjutan</li>
        </ul>
      </section>

      <section>
        <h2>🌱 Proyek Terbaru</h2>
        <p>
          <strong>Aplikasi Pendaftaran Kegiatan Kampus</strong> – dibuat menggunakan Vue.js dengan fitur login peran (Admin & Mahasiswa).
        </p>
      </section>

      <section>
        <h2>✨ Motto Hidup</h2>
        <blockquote>
          "Terus belajar, terus berkembang, dan jangan pernah takut mencoba hal baru."
        </blockquote>
      </section>
    </div>
  </div>
</template>

<script setup>
// Tidak ada logic tambahan saat ini
</script>

<style scoped>
/* Gradasi latar belakang yang lembut */
.portfolio-wrapper {
  min-height: 100vh;
  padding: 2rem;
  background: linear-gradient(135deg, #d8f3dc, #f3e8ff);
  display: flex;
  justify-content: center;
  align-items: center;
}

.portfolio-container {
  background: white;
  max-width: 850px;
  width: 100%;
  padding: 2.5rem;
  border-radius: 24px;
  box-shadow: 0 14px 40px rgba(0, 0, 0, 0.12);
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.8;
  animation: fadeIn 1.2s ease-in-out;
  transition: transform 0.3s ease;
}

.portfolio-container:hover {
  transform: scale(1.01);
}

h1 {
  text-align: center;
  font-size: 2.4rem;
  color: #7b2cbf;
  margin-bottom: 1rem;
}

h2 {
  color: #5f0f40;
  margin-top: 2rem;
  border-bottom: 2px solid #e6d1f2;
  padding-bottom: 0.3rem;
  font-size: 1.4rem;
}

ul {
  list-style: none;
  padding-left: 0;
}

ul li {
  background-color: #f6f2ff;
  padding: 0.5rem 1rem;
  margin-bottom: 0.4rem;
  border-left: 4px solid #a25ddc;
  border-radius: 8px;
  transition: background 0.3s;
}

ul li:hover {
  background-color: #e7dbff;
}

ul li span {
  font-weight: bold;
}

blockquote {
  background: #f3ecff;
  padding: 1rem 1.2rem;
  border-left: 6px solid #a25ddc;
  font-style: italic;
  color: #4e3170;
  border-radius: 10px;
  margin-top: 0.5rem;
}

/* Animasi */
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: scale(0.95);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

/* Responsive mobile */
@media screen and (max-width: 600px) {
  .portfolio-container {
    padding: 1.2rem;
    border-radius: 12px;
  }

  h1 {
    font-size: 1.8rem;
  }

  h2 {
    font-size: 1.2rem;
  }

  ul li {
    font-size: 0.95rem;
    padding: 0.6rem 0.8rem;
  }

  blockquote {
    font-size: 0.95rem;
  }
}
</style>
