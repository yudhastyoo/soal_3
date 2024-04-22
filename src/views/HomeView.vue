<template>
  <div class="home">
    <div class="card-list">
      <div class="card">
        <img src="../assets/gambar1.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar2.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar3.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar4.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar1.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar2.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar3.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
      <div class="card">
        <img src="../assets/gambar4.webp" alt="" />
        <div class="title-rating">
          <h5>Kediri, Indonesia</h5>
          <span>&#9733; 4.3</span>
        </div>
        <div class="desc">
          <span>Pemandangan pegunungan</span>
          <span>5 Malam &centerdot; 18-23 Maret</span>
        </div>
        <div class="price"><span>Rp6.123.123</span> total sebelum pajak</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeView",
};
</script>

<style>
.home {
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}
.card-list {
  display: flex;
  flex-wrap: wrap;
  gap: 60px;
}

.card {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.card img {
  border-radius: 10px;
  width: 300px;
  height: 250px;
}

.card .title-rating {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.card .desc {
  display: flex;
  flex-direction: column;
  font-size: 12px;
  color: rgb(155, 155, 155);
}

.card .price {
  font-weight: 400;
}
.card .price span {
  font-weight: 600;
}
</style>
