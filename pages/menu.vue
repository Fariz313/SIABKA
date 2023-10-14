<template>
  <div class="d-flex flex-column vh-100">
    <div class="container-fluid overflow-hidden px-5 mb-3">
      <div class="row mb-2 mt-3">
        <div class="col-12">
          <div class="d-flex">
            <img
              src="@/assets/profile.jpg"
              height="50px"
              width="50px"
              class="profile-photo mr-3 my-auto"
              alt=""
              srcset=""
            />
            <div class="d-flex flex-column">
              <p class="mb-0 mt-3">Selamat Datang !<b>Pak John</b></p>
              <p class="mb-3">Admin</p>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-2 logo-bg"></div>
        <div class="col-10">
          <div class="input-group my-auto">
            <input
              type="text"
              class="form-control"
              placeholder="Recipient's username"
              aria-label="Recipient's username"
              aria-describedby="button-addon2"
            />
            <button class="btn btn-success" type="button" id="button-addon2">
              Cari
            </button>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid bg-white bottom-flex bottom-flex flex-grow-1">
      <h6>Pilih Kategori ABK</h6>
      <div class="row text-center mb-3">
        <div class="col-3">
          <nuxt-link to="/pengelihatan">
            <div
              class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
              style="width: 70px; height: 70px; font-size: 30px; color: white"
            >
              <i class="fa-solid fa-eye text-white"></i>
            </div>
            <p class="p-card">Pengelihatan</p>
          </nuxt-link>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-solid fa-ear-listen"></i>
          </div>
          <p class="p-card">Pendengaran</p>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-solid fa-brain"></i>
          </div>
          <p class="p-card">Intelektual</p>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-solid fa-hands"></i>
          </div>
          <p class="p-card">Motor Fisik</p>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-regular fa-face-grin-wide"></i>
          </div>
          <p class="p-card">Emosional</p>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-solid fa-face-meh-blank"></i>
          </div>
          <p class="p-card">Autisme</p>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-solid fa-person-running"></i>
          </div>
          <p class="p-card">ADHD</p>
        </div>
        <div class="col-3">
          <div
            class="rounded-circle bg-primary d-flex align-items-center justify-content-center p-1 mx-auto my-1"
            style="width: 70px; height: 70px; font-size: 30px; color: white"
          >
            <i class="fa-solid fa-border-all"></i>
          </div>
          <p class="p-card">See All</p>
        </div>
      </div>
      <h6>Artikel Inklusif</h6>
      <div class="row mb-3">
        <div class="col-4">
          <img
            src="@/assets/article-example.png"
            class="w-100 h-100"
            style="border-radius: 15px"
            alt=""
            srcset=""
          />
        </div>
        <div class="col-4">
          <img
            src="@/assets/article-example.png"
            class="w-100 h-100"
            style="border-radius: 15px"
            alt=""
            srcset=""
          />
        </div>
        <div class="col-4">
          <img
            src="@/assets/article-example.png"
            class="w-100 h-100"
            style="border-radius: 15px"
            alt=""
            srcset=""
          />
        </div>
      </div>
      <h6>Sekolah Inklusif Banyuwangi</h6>
      <div class="row">
        <div class="col-6">
          <img
            src="@/assets/article-example.png"
            class="w-100 h-100"
            style="border-radius: 15px"
            alt=""
            srcset=""
          />
        </div>
        <div class="col-6">
          <img
            src="@/assets/article-example.png"
            class="w-100 h-100"
            style="border-radius: 15px"
            alt=""
            srcset=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
