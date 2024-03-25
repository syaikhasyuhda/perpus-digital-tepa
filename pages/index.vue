<template>
  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung/tambah">
          <div class="card bg-pengunjung rounded-5">
            <div class="card-body">
              <h2>pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
      <div class="col-lg-6">
        <nuxt-link to="/buku/">
          <div class="card bg-buku rounded-5">
            <div class="card-body">
              <h2>cari buku</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>

  <div class="Container-fluid">
    <div class="row justify-cotent-evenly rounded-3">
      <div class="col-5">
        <div class="cardi">
          <div class="melanie">
            <h2>3 pengunjung</h2>
          </div>
        </div>
      </div>
      <div class="col-5">
        <div class="melanie1">
          <h2>180 Buku</h2>
        </div>
      </div>
    </div>
  </div>
  <div class="line">
    <statistik />
  </div>
</template>

<style scoped>
.v2 {
  height: 3px;
  width: 98%;
  margin-left: 30px;
  border-left: 3px solid black;
  background-color: black;
}

.v1 {
  margin-top: 40px;
  margin-left: 30px;
  border-left: 3px solid black;
  height: 400px;
}

.card {
  height: 250px;
  box-shadow: 1px 1px 10px #424242;
}

.card.bg-pengunjung {
  background-image: url('../assets/img/kunjungan.png');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

.card.bg-buku {
  background: url('../assets/img/cari buku.png');
  background-size: cover;
}

.syaika {
  height: 200px;
  box-shadow: 1px 1px 10px;
  border-radius: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #E4CA6B;
}

.syaika1 {
  height: 200px;
  box-shadow: 1px 1px 10px;
  border-radius: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #1DDD81
}
</style>