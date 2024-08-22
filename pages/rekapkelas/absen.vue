<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center"> Presensi Kelas</h2>
        <form>
          <div class="mb-3">
            <input type="text" class="form-control form-control-lg rounded-5" placeholder="Nama Guru.....">
          </div>
            <div class="mb-3">
              <div class="row">
                <div class="col-md-4">
            <select class="form-control form-control-lg form-select rounded-5 ">
              <option value="">KELAS</option>
              <option value="10">10</option>
              <option value="11">11</option>
              <option value="12">12</option>
            </select>
          </div>
          
            <div class="col-md-4">
            <select class="form-control form-control-lg form-select rounded-5 ">
              <option value="">Jurusan</option>
              <option value="PPLG">PPLG</option>
              <option value="TJKT">TJKT</option>
              <option value="TBSM">TBSM</option>
              <option value="DKV">DKV</option>
              <option value="TOI">TOI</option>
            </select>
          </div>
              <div class="col-md-4">
            <select class="form-control form-control-lg form-select rounded-5 ">
              <option value="">Tingkat</option>
              <option value="PPLG">1</option>
              <option value="TJKT">2</option>
              <option value="TBSM">3</option>
              <option value="DKV">4</option>
            </select>
          </div>
            </div>
              </div>
          <div class="col-md-12 ">
            <input type="number" class="form-control form-control-lg rounded-5" placeholder="Total Siswa..">
              </div>
              <div class="mb-4">
                <div class="row">
                  <div class="col-md-4 p-2">
                    <input type="number" class="form-control form-control-lg rounded-5" placeholder="Hadir..">
              </div>
              <div class="col-md-4 p-2">
                <input type="number" class="form-control form-control-lg rounded-5" placeholder="Tidak Hadir..">
              </div>
              <div class="col-md-4 p-2">
                <input type="number" class="form-control form-control-lg rounded-5" placeholder="Sakit..">
            </div>
            <div class="col-md-4 p-2">
              <input type="number" class="form-control form-control-lg rounded-5" placeholder="Izin..">
            </div>
            <div class="col-md-4 p-2">
              <input type="number" class="form-control form-control-lg rounded-5" placeholder="Alpa..">
            </div>
            <div class="col-md-4 p-2">
              <input type="number" class="form-control form-control-lg rounded-5" placeholder="Dispen..">
            </div>
            </div>
          </div>
        </form>
        
      </div>
      <NuxtLink to="/rekapkelas" class="col-lg-6 d-flex justify-content-end">
          <button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">kirim</button>
        </NuxtLink>
        <NuxtLink to="/" class="col-lg-6 d-flex justify-content-start">
          <button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">kembali</button>
        </NuxtLink>
    </div>
  </div>
</template>