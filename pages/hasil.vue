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
      <div class="row text-center">
        <h1 class="w-100 display-1 my-5 font-weight-bold">36</h1>
      </div>
    </div>
    <div class="container-fluid bg-white bottom-flex bottom-flex flex-grow-1 text-center">
      <h1 class="text-danger">Hasil Diagnosa</h1>
      <h1 class="w-100 display-4 my-5 font-weight-bold">"Dislexia"</h1>
      <p>
        Berdasarkan perhitungan instrumen user diduga mengalami dislexia ringa..
        Mohon segera di bawa ke dokter spesialis terdekat
      </p>
      <button class="btn btn-success mb-5">Print Excel</button>
      <button @click="$router.push('/menu');" class="btn btn-danger">Akhiri Test</button>
    </div>
  </div>
</template>

