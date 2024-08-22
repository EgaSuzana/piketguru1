<template>
  <div class="container-fluid">
    <div class="row my-5 rounded-5">
      <div class="row d-flex justify-content-center">
      <div class="col-lg-6">
        <nuxt-link to="/rekapkelas/absen">
          <div class="card bg-kelas rounded-5 m-3">
            <div class="card-body">
              <h2>piket mengontrol kelas</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
      </div>
      <div class="col-lg-6">
        <nuxt-link to="/rekapizinsiswa/siswa">
          <div class="card bg-loby rounded-5 m-3 ">
            <div class="card-body">
              <h2> Izin Siswa</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
        <div class="col-lg-6">
          <nuxt-link to="/rekapizintamu/tamu">
            <div class="card bg-tamu rounded-5 m-3 ">
              <div class="card-body">
                <h2> Izin Tamu</h2>
              </div>
            </div>
          </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  height: 250px;
  box-shadow: 1px 1px 10px #424242;
}
.card.bg-kelas {
  background-image: url("../assets/kampus.jpg");
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
.card.bg-loby {
  background-image: url("../assets/murid.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center; 
}
.card.bg-tamu {
  background-image: url("../assets/tamu1.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center; 
}

</style>