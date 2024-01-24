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
        <div class="col-12 mb-5">
          <img
            src="@/assets/belajar.jpg"
            class="w-100 h-100"
            style="border-radius: 50px"
            alt=""
            srcset=""
          />
        </div>
        <div class="col-12">
          <h3 class="mb-0 text-white">Kategori Hambatan</h3>
          <h1 class="text-danger">Slow Learner</h1>
          <span class="btn btn-light">Indikator 1:</span>
          <p class="text-white">
            Sering lambat dalam menyelesaikan tugas-tugas akademik?
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-6">
          <button @click="$router.push('/normal');"
            class="w-100 btn btn-info"
            style="height: 80px; border-radius: 10px;vertical-align:middle  "
          >
            <b> Tidak </b>
          </button>
        </div>
        <div class="col-6">
          <button @click="$router.push('/hasil');"
            class="w-100 btn btn-danger"
            style="height: 80px; border-radius: 10px;vertical-align:middle  "
          >
            <b> YA </b>
          </button>
        </div>
      </div>
    </div>
    <!-- <div class="container-fluid bg-white bottom-flex bottom-flex flex-grow-1">
      
    </div> -->
  </div>
</template>

