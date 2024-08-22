<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-3">REKAPITULASI IZIN TAMU</h2>
        <div class="my-3">
          <input type="text" class="form-control form-control-lg rounded-5" placeholder="Nama">
        </div>
        <div class="my-3">
          <select class="form-control form-control-lg form-select rounded-5 ">
            <option value="">Keanggotaan</option>
            <option value="Siswa">Tamu</option>
          </select>
        </div>
        <div class="my-3">
          <select class="form-control form-control-lg form-select rounded-5 ">
            <option value="">Keperluan</option>
            <option value="Pulang">Memberikan Bekal </option>
            <option value="Pulang">Keluar Membawa Barang Yang Ketinggalan</option>
            <option value="Pulang">Izin Dispen</option>
          </select>
        </div>
      </div>
      <NuxtLink to="/rekapizintamu" class="col-lg-6 d-flex justify-content-end">
          <button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">Kirim</button>
        </NuxtLink>
        <NuxtLink to="/" class="col-lg-6 d-flex justify-content-start">
          <button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">Kembali</button>
        </NuxtLink>
    </div>
  </div>
  </template>