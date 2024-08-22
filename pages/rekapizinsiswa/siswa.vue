<template>
<div class="container-fluid">
  <div class="row">
    <div class="col-lg-12">
      <h2 class="text-center my-3">FORM IZIN SISWA</h2>
      <div class="my-3">
        <input type="text" class="form-control form-control-lg rounded-5" placeholder="Nama">
      </div>
      <div class="my-3">
        <select class="form-control form-control-lg form-select rounded-5 ">
          <option value="">Keanggotaan</option>
          <option value="Siswa">Siswa</option>
        </select>
      </div>
      <div class="mb-3">
        <div class="row">
          <div class="col-md-4">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="Kelas">Kelas</option>
              <option value="10">10</option>
              <option value="11">11</option>
              <option value="12">12</option>
            </select>
          </div>
          <div class="col-md-4">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="Jurusan">Jurusan</option>
              <option value="TJKT">TJKT</option>
              <option value="PPLG">PPLG</option>
              <option value="TBSM">TBSM</option>
              <option value="DKV">DKV</option>
              <option value="TOI">TOI</option>
            </select>
          </div>
          <div class="col-md-4">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="Tingkat">Tingkat</option>
              <option value="1">1</option>
              <option value="2">2</option>
              <option value="3">3</option>
              <option value="4">4</option>
            </select>
          </div>
        </div>
      </div>
      <div class="my-3">
        <select class="form-control form-control-lg form-select rounded-5 ">
          <option value="">Keperluan</option>
          <option value="Pulang">Pulang(Sakit)</option>
          <option value="Pulang">Keluar Membawa Barang Yang Ketinggalan</option>
          <option value="Pulang">Izin Dispen</option>
        </select>
      </div>
    </div>
    <div class="kirim col-lg-6 d-flex justify-content-end">
    <NuxtLink to="/rekapizinsiswa">
          <button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">kirim</button>
        </NuxtLink>
      </div>
      <div class="kirim col-lg-6 d-flex justify-content-start">
        <NuxtLink to="/">
          <button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">kembali</button>
        </NuxtLink></div>
  </div>
</div>
</template>