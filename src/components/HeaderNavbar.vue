<template>
  <div class="wrapper">
    <div class="navbar">
      <img src="../assets/airbnb.png" width="200" />
      <nav>
        <div class="nav-1">Tempat Menginap</div>
        <div class="nav-2">Pengalaman</div>
        <div class="nav-3">Pengalaman Online</div>
      </nav>
      <div class="account">
        <div>Jadikan rumah Anda Airbnb</div>
        <div class="profile">
          <img src="../assets/menu.png" width="20" alt="" />
          <img src="../assets/user.png" width="20" alt="" />
        </div>
      </div>
    </div>
    <div class="search-bar">
      <div class="search-box lokasi">
        <label for="lokasi">Lokasi</label>
        <input type="text" placeholder="Cari destinasi" />
      </div>
      <div class="search-box lokasi">
        <label for="lokasi">Check in</label>
        <input type="text" placeholder="Tambahkan.." />
      </div>
      <div class="search-box lokasi">
        <label for="lokasi">Check out</label>
        <input type="text" placeholder="Tambahkan.." />
      </div>
      <div class="search-box lokasi">
        <label for="lokasi">Peserta</label>
        <input type="text" placeholder="Tambahkan tamu" />
      </div>
      <button class="search-btn">
        <img src="../assets/search.png" width="20" alt="" />
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderNavbar",
  setup() {
    return {};
  },
};
</script>

<style scoped>
.wrapper {
  padding: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  border-bottom: 1px solid #ccc;
  padding-bottom: 10px;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}

nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  gap: 20px;
  cursor: pointer;
}

.nav-1 {
  font-weight: 600;
}

.navbar .account {
  display: flex;
  align-items: center;
  gap: 7px;
}

.profile {
  border: 1px solid #000;
  display: flex;
  align-items: center;
  border-radius: 10px;
  padding: 10px;
  gap: 10px;
  cursor: pointer;
}

.profile img:last-child {
  border: 1px solid #000;
  background: #b3b3b3;
  padding: 2px;
  border-radius: 50%;
}

.search-bar {
  display: flex;
  border: 1px solid #000;
  border-radius: 30px;
  padding: 10px 20px;
  margin-top: -30px;
  box-shadow: 1px 6px 16px -4px rgba(0, 0, 0, 0.75);
}

.search-box {
  display: flex;
  flex-direction: column;
  border-right: 1px solid #6b6b6b;
  margin-right: 10px;
}

.search-box input {
  border: none;
  background: none;
}

.search-box input:focus {
  outline: none;
}

.search-box:first-child {
  margin-right: 40px;
}

.search-box:nth-child(4) {
  border-right: none !important;
}

.search-btn {
  display: flex;
  align-items: center;
  padding: 20px;
  border-radius: 50%;
  border: none;
  background-color: rgb(254, 113, 113);
  cursor: pointer;
}
</style>
