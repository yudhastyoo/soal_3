<template>
  <div class="home" :class="{ scrolled: isScrolled }">
    <div class="card-list">
      <div class="card">
        <div id="carouselExampleIndicators" class="carousel slide">
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="3"
              aria-label="Slide 4"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/gambar1.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar2.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar3.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar4.webp" class="d-block w-100" />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <!-- <img src="../assets/gambar1.webp" alt="" /> -->
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
        <div id="carouselExampleIndicators2" class="carousel slide">
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="3"
              aria-label="Slide 4"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/gambar2.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar3.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar4.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar1.webp" class="d-block w-100" />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleIndicators2"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleIndicators2"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <!-- <img src="../assets/gambar1.webp" alt="" /> -->
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
        <div id="carouselExampleIndicators3" class="carousel slide">
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="3"
              aria-label="Slide 4"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/gambar3.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar4.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar1.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar2.webp" class="d-block w-100" />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleIndicators3"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleIndicators3"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <!-- <img src="../assets/gambar1.webp" alt="" /> -->
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
        <div id="carouselExampleIndicators4" class="carousel slide">
          <div class="carousel-indicators">
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleIndicators"
              data-bs-slide-to="3"
              aria-label="Slide 4"
            ></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/gambar4.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar1.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar2.webp" class="d-block w-100" />
            </div>
            <div class="carousel-item">
              <img src="../assets/gambar3.webp" class="d-block w-100" />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleIndicators4"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleIndicators4"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <!-- <img src="../assets/gambar1.webp" alt="" /> -->
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
import { ref } from "vue";

export default {
  name: "HomeView",
  setup() {
    const isScrolled = ref(false);
    const handleScroll = () => {
      isScrolled.value =
        document.body.scrollTop > 0 || document.documentElement.scrollTop > 0;
    };

    window.addEventListener("scroll", handleScroll);

    return {
      isScrolled,
    };
  },
};
</script>

<style>
.home {
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  transition: transform 400ms;
}

.home.scrolled {
  transform: translateY(140px);
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
  border: none !important;
}

.card img {
  border-radius: 10px;
  width: 300px;
  height: 250px;
}

.carousel {
  width: 300px;
  height: 250px;
}

.carousel-inner {
  border-radius: 10px;
}

.carousel-indicators [data-bs-target] {
  width: 10px !important;
  height: 10px !important;
  border-radius: 50%;
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
