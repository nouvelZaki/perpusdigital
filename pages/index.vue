<template>
  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung/tambah">
          <div class="card bg-pengunjung rounded-5">
            <div class="card-body">
              <h2>Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
      <div class="col-lg-6">
        <nuxt-link to="/buku">
          <div class="card bg-buku rounded-5">
            <div class="card-body">
              <h2>Cari Buku</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>
  <h1 class="statistik">STATISTIK</h1>
  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung">
          <div class="card bg-light rounded-5">
            <div class="card-body">
              <h2>5 Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    

      <div class="col-lg-6">
          <div class="card bg-light rounded-5">
            <div class="card-body">
              <h2>Stock 19 Buku</h2>
            </div>
          </div>
      </div>
    </div>
  </div>


</template>

<style scoped>
.card {
  height: 250px;
  box-shadow: 1px 1px 1px #424242;
}
.card.bg-pengunjung {
  background-image: url('~/assets/bgkunjungan.jpeg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
.card.bg-buku {
  background-image: url('~/assets/bgbuku.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;      
}
.statistik{
  left: reight;
}
</style>