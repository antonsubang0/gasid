<script setup>
import TheWelcome from "../components/TheWelcome.vue";
</script>

<template>
  <!-- navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-yellow fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#"
        ><img src="../assets/logo.png" alt="" class="logo-nav"
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a
              class="nav-link fw-bold text-start fs-6 active"
              aria-current="page"
              href="#"
              >Beranda</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold text-start fs-6" href="#">Tentang GAS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold text-start fs-6" href="#">Fitur</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold text-start fs-6" href="#">Daftar</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold text-start fs-6 me-2" href="#">Karir</a>
          </li>
          <li class="nav-item">
            <button
              class="btn btn-primary bg-bluee fw-bold text-start fs-6"
              href="#"
              target="_blank"
            >
              Masuk Mitra
            </button>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- section1 -->
  <div class="row gx-0 mt-5 p-5 bg-1">
    <div
      class="
        col-12 col-md-6
        d-flex
        justify-content-center
        align-items-center
        p-5
      "
    >
      <div>
        <h3 class="text-primary fs-3 fw-bold">Bergabung dengan GAS</h3>
        <p>
          Aplikasi untuk memudahkan pelaku usaha menjangkau calon pembeli lebih
          luas. Daftarkan tokomu dan nikmati keuntungan bersama GAS!
        </p>
        <button class="btn btn-primary btn-bluee1">Unduh Sekarang</button>
      </div>
    </div>
    <div
      class="
        col-12 col-md-6
        d-flex
        justify-content-center
        align-items-center
        p-5
      "
    >
      <img src="../assets/ilustration_top.png" class="img-fluid ill-1" alt="" />
    </div>
  </div>
  <!-- section2 -->
  <div class="row gx-0 p-5 bg-bluee">
    <div
      class="
        col-12 col-md-6
        d-flex
        justify-content-center
        align-items-center
        p-5
      "
    >
      <div>
        <h3 class="text-white fs-4 fw-bold">
          GAS adalah aplikasi untuk memudahkan pelaku usaha menjangkau calon
          pembeli lebih luas. Melalui gerakan #AyoBelanjaTokoTetangga GAS
          mengajak untuk menjelajah dan mendukung usaha-usaha di sekitarmu.
        </h3>
      </div>
    </div>
    <div
      class="
        col-12 col-md-6
        d-flex
        justify-content-center
        align-items-center
        p-5
      "
    >
      <div
        id="carouselExampleSlidesOnly"
        class="carousel slide"
        data-bs-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/gambar-pembeli.png" class="d-block" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/gambar-driver.png" class="d-block" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/gambar-toko.png" class="d-block" alt="..." />
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- section3 -->
  <div class="row gx-0 p-5 bg-2">
    <div
      class="
        col-12 col-md-6
        d-flex
        justify-content-center
        align-items-center
        p-5
      "
    >
      <div>
        <h3 class="text-primary fs-4 fw-bold">
          Ayo Nikmati Beragam Fitur GAS dan Kembangkan Usahamu Jadi Toko Online
        </h3>
      </div>
    </div>
    <div
      class="
        col-12 col-md-6
        d-flex
        justify-content-center
        align-items-center
        p-5
      "
    >
      <div
        id="carouselExampleSlidesOnly1"
        class="carousel slide"
        data-bs-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/1.png" class="d-block" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/2.png" class="d-block" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/3.png" class="d-block" alt="..." />
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- section4 -->
  <div class="row gx-0 p-5 bg-2">
    <div class="col-12 text-center p-5">
      <h3 class="fs-4 fw-bold mb-3">
        Apa pun jenis tokomu bisa bergabung bersama GAS
      </h3>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/VxVWACx9NIY"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>
  </div>
  <!-- section5 -->
  <div class="row gx-0 mt-5 p-5 bg-3 text-center">
    <h3 class="text-white fs-3 fw-bold">Temukan Karier Impianmu</h3>
    <p class="text-white">
      Mari bergabung bersama kami. Jadilah bagian dari kami dan kembangkan
      bakat, kreatifmu di GAS
    </p>
    <div class="col-12">
      <div class="row">
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 p-5">
          <div class="row">
            <div class="col-3">
              <img
                src="../assets/digitalmarketing.png"
                alt=""
                class="img-fluid"
              />
            </div>
            <div class="col-9">
              <h3 class="text-yellow text-start fs-5">
                Marketing Communication
              </h3>
              <p class="text-start text-white">
                Merancang strategi komunikasi pemasaran mulai dari branding,
                iklan dan pemasaran langsung.
              </p>
              <div class="text-end">
                <button class="btn btn-primary yellow">
                  Baca Selengkapnya
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- footer -->
  <div class="bg-yellow">
    <div class="container p-5">
      <div class="row">
        <div class="col-3 col-md-1">
          <img src="../assets/logo.png" alt="" class="img-fluid" />
        </div>
        <div class="col-4 col-md-3">
          <h4>Tentang GAS</h4>
          <p>Terms and Conditions Privacy</p>
        </div>
        <div class="col-4 col-md-3">
          <h4>Hubungi Kami</h4>
          <p>Kritik dan saran</p>
          <p>&nbsp;</p>
        </div>
        <div class="col-4 col-md-3">
          <h4>Ikuti Kami</h4>
          <p>Terms and Conditions Privacy</p>
        </div>
        <div class="col-4 col-md-2">
          <h4>Unduh</h4>
          <p>....</p>
        </div>
      </div>
    </div>
  </div>
</template>
