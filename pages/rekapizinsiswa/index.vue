<template>
<div class="container-fluid">
  <div class="row">
    <div class="col-lg-12">
      <h2 class="text-center">Rekapitulasi Izin Siswa</h2>
      <input type="text" class="form-control form-control-lg " placeholder="filter....">
      <div class="my-3 text-muted">Menampilkan 1 dari 1</div>
      <table class="table" style="width:100%">
        <thead>
          <tr>
            <th>No</th>
            <th>Nama</th>
            <th>Keanggotaan</th>
            <th>Kelas</th>
            <th>Jurusan</th>
            <th>Waktu</th>
            <th>Tanggal</th>
            <th>Keperluan</th>
          </tr>
        </thead>
      </table>
    </div>
    <NuxtLink to="/rekapizinsiswa/siswa" class="col-lg-6 d-flex justify-content-end">
      <button class="btn btn-primary btn-lg rounded-5 ">Tambah Data</button>
    </NuxtLink>
    <NuxtLink to="/" class="col-lg-6 d-flex justify-content-start">
      <button class="btn btn-primary btn-lg rounded-5 ">Kembali</button>
    </NuxtLink>
  </div>
</div>
</template>
<style scoped>
table ,th, td{
  border: 1px solid black;
  border-collapse: collapse;
}

</style>