<template>
<div class="container-fluid">
  <div class="row">
    <div class="col-lg-12">
      <h2 class="text-center my-3">REKAPITULASI ABSENSI KELAS</h2>
      <div class="my-3">
        <input type="text" class="form-control form-control-lg rounded-5" placeholder="kelas...">
      </div>
      <div class="my-3 text-muted">menampilkan 1 dari 1</div>
      <table style="width:100%" class="table text-center">
  <tr>
    <th rowspan="2">No</th>
    <th rowspan="2">Kelas</th>
    <th rowspan="2">Guru</th>
    <th colspan="3">Jumlah Siswa</th>
    <th colspan="5">Keterangan</th>
  </tr>
  <tr>
    <th>Total</th>
    <th>Hadir</th>
    <th>Tidak Hadir</th>
    <th> S </th>
    <th> I </th> 
    <th> A </th>
    <th> D </th>
  </tr>
  <tr>
    <td>1</td>
    <td>RPL 10</td>
    <td>Bu Haji</td>
    <td>25</td>
    <td>21</td>
    <td>4</td>
    <td>1</td>
    <td>2</td>
    <td>1</td>
    <td>100</td>
  </tr>
</table>
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

<style scoped>
table ,th, td{
  border: 1px solid black;
  border-collapse: collapse;
}

</style>