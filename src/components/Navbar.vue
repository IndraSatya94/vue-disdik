<template>
   <div class="container-fluid container-xl d-flex align-items-center justify-content-between">

      <div class="logoheader d-flex align-items-center">
        <img src="assets/img/logobolmong.png" alt="">
        <h1 class="logo"><a href="index.html">DINAS <br> PENDIDIKAN</a></h1>
      </div>


      <nav class="nav-menu d-none d-lg-block">

        <ul>
          <li class="active"><a href="index.html">Beranda</a></li>

          <li class="drop-down"><a href="#">Profil</a>
            <ul>
              <li><a href="tugasfungsi.html">Tugas dan Fungsi</a></li>
              <li><a href="sambutan.html">Sambutan Kepala Dinas</a></li>
              <li><a href="visimisi.html">Visi & Misi</a></li>
              <li><a href="struktur.html">Struktur Organisasi</a></li>
            </ul>
          </li>

          <li><a href="berita.html">Berita</a></li>
          <li><a href="agenda.html">Agenda</a></li>
          <li class="drop-down"><a href="#">Standar Pelayanan</a>
                <ul>
                  <li class="drop-down"><a href="#">Bidang PAUD DIKMAS</a>
                    <ul>
                      <li><a href="pagesubmenu/bidangpaud/izinpembelajaran.html">Izin Pembelajaran Luar Kelas</a></li>
                      <li><a href="pagesubmenu/bidangpaud/legalisasiijazah.html">Legalisasi Ijazah Nonformal</a></li>
                      <li><a href="pagesubmenu/bidangpaud/penggantiijazah.html">Pengganti Ijazah Nonformal</a></li>
                      <li><a href="pagesubmenu/bidangpaud/pembetulanijazah.html">Pembetulan Ijazah/SHUN</a></li>
                      <li><a href="pagesubmenu/bidangpaud/izinpendirian.html">Izin Pendirian</a></li>
                    </ul>
                  </li>
                  <li class="drop-down"><a href="#">Bidang SD</a>
                    <ul>
                      <li><a href="pagesubmenu/bidangsd/izinpembelajaran.html">Izin Pembelajaran Luar Kelas</a></li>
                      <li><a href="pagesubmenu/bidangsd/legalisasiijazah.html">Legalisasi Ijzah SD</a></li>
                      <li><a href="pagesubmenu/bidangsd/mutasisiswa.html">Mutasi Siswa SD</a></li>
                      <li><a href="pagesubmenu/bidangsd/penggantiijazah.html">Pengganti Ijazah</a></li>
                      <li><a href="pagesubmenu/bidangsd/pembetulanijazah.html">Pembetulan Ijazah/SHUN</a></li>
                      <li><a href="pagesubmenu/bidangsd/izinpendirian.html">Izin Pendirian SD</a></li>
                    </ul>
                  </li>
                  <li class="drop-down"><a href="#">Bidang SMP</a>
                    <ul>
                      <li><a href="pagesubmenu/bidangsmp/izinpembelajaran.html">Izin Pembelajaran Luar Kelas</a></li>
                      <li><a href="pagesubmenu/bidangsmp/legalisasiijazah.html">Legalisasi Ijzah SMP</a></li>
                      <li><a href="pagesubmenu/bidangsmp/mutasisiswa.html">Mutasi Siswa SMP</a></li>
                      <li><a href="pagesubmenu/bidangsmp/penggantiijazah.html">Pengganti Ijazah</a></li>
                      <li><a href="pagesubmenu/bidangsmp/pembetulanijazah.html">Pembetulan Ijazah/SHUN</a></li>
                      <li><a href="pagesubmenu/bidangsmp/izinpendirian.html">Izin Pendirian SMP</a></li>
                    </ul>
                  </li>
                  <li class="drop-down"><a href="#">Sekretariat</a>
                    <ul>
                      <li><a href="pelayanandata.html">Pelayanan Data</a></li>
                      <li><a href="aduanmasyarakat.html">Aduan Masyarakat</a></li>
                    </ul>
                  </li>
            </ul>
              </li>
              <li class="drop-down"><a href="#">GTK</a>
                <ul>
                  <li><a href="pagesubmenu/GTK/usuljabatan.html">Usul Jabatan</a></li>
                  <li><a href="pagesubmenu/GTK/sertifikasiguru.html">Sertifikasi Guru</a></li>
                  <li><a href="pagesubmenu/GTK/urusankepegawaian.html">Urusan Kepegawaian</a></li>
                  <li><a href="pagesubmenu/GTK/mutasi.html">Mutasi Antar Daerah</a></li>
                  <li><a href="pagesubmenu/GTK/izintugasbelajar.html">Izin dan Tugas Belajar</a></li>
                  <li><a href="pagesubmenu/GTK/pengajuancuti.html">Pengajuan Cuti</a></li>
                </ul>
              </li>
              <li><a href="https://ppid.bolmongkab.go.id">PPID</a></li>
              <li><a href="galeri.html">Dokumentasi</a></li>
              <li><a href="kontak.html">Kontak</a></li>
            </ul>

      </nav><!-- .nav-menu -->

    </div>
</template>

<script>
export default {
    name:'Navbar'
}
</script>

<style>
/*--------------------------------------------------------------
# Navigation Menu
--------------------------------------------------------------*/
/* Desktop Navigation */
.align-items-center {
    align-items: center !important;
    background: #063A69;
}

.align-items-center a {
    color: #fff;
}

.nav-menu ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

.nav-menu > ul {
  display: flex;
}

.nav-menu > ul > li {
  position: relative;
  white-space: nowrap;
  padding: 12px 0 12px 28px;
}

.nav-menu a {
  display: block;
  position: relative;
  color: #ffffff;
  transition: 0.3s;
  font-size: 15px;
  font-weight: 500;
  /* font-family: "Poppins", sans-serif; */
}

.nav-menu a:hover, .nav-menu .active > a, .nav-menu li:hover > a {
  color: #4154f1 ;
}

.nav-menu .drop-down ul {
  display: block;
  position: absolute;
  left: 15px;
  top: calc(100% + 30px);
  z-index: 99;
  opacity: 0;
  visibility: hidden;
  padding: 10px 0;
  background: #fff;
  box-shadow: 0px 0px 30px rgba(127, 137, 161, 0.25);
  transition: 0.3s;
}

.nav-menu .drop-down:hover > ul {
  opacity: 1;
  top: 100%;
  visibility: visible;
}

.nav-menu .drop-down li {
  min-width: 180px;
  position: relative;
}

.nav-menu .drop-down ul a {
  padding: 10px 20px;
  font-size: 14px;
  font-weight: 500;
  text-transform: none;
  color: #556270;
}

.nav-menu .drop-down ul a:hover, .nav-menu .drop-down ul .active > a, .nav-menu .drop-down ul li:hover > a {
  color: #4154f1 ;
}

.nav-menu .drop-down > a:after {
  content: "\ea99";
  font-family: IcoFont;
  padding-left: 5px;
}

.nav-menu .drop-down .drop-down ul {
  top: 0;
  left: calc(100% - 30px);
}

.nav-menu .drop-down .drop-down:hover > ul {
  opacity: 1;
  top: 0;
  left: 100%;
}

.nav-menu .drop-down .drop-down > a {
  padding-right: 35px;
}

.nav-menu .drop-down .drop-down > a:after {
  content: "\eaa0";
  font-family: IcoFont;
  position: absolute;
  right: 15px;
}

@media (max-width: 1366px) {
  .nav-menu .drop-down .drop-down ul {
    left: -90%;
  }
  .nav-menu .drop-down .drop-down:hover > ul {
    left: -100%;
  }
  .nav-menu .drop-down .drop-down > a:after {
    content: "\ea9d";
  }
}

/* Get Startet Button */
.get-started-btn {
  margin-left: 25px;
  background: #F8A50B ;
  color: #fff;
  border-radius: 4px;
  padding: 8px 30px 9px 30px;
  white-space: nowrap;
  transition: 0.3s;
  font-size: 14px;
  display: inline-block;
}

.get-started-btn:hover {
  background: #F8A50B ;
  color: #fff;
}

@media (max-width: 991px) {
  .get-started-btn {
    margin: 0 48px 0 0;
    padding: 6px 18px;
  }
}

/* Mobile Navigation */
.mobile-nav-toggle {
  position: fixed;
  right: 15px;
  top: 15px;
  z-index: 9998;
  border: 0;
  background: none;
  font-size: 24px;
  transition: all 0.4s;
  outline: none !important;
  line-height: 1;
  cursor: pointer;
  text-align: right;
}

.mobile-nav-toggle i {
  color: #556270;
}

.mobile-nav {
  position: fixed;
  top: 55px;
  right: 15px;
  bottom: 15px;
  left: 15px;
  z-index: 9999;
  overflow-y: auto;
  background: #fff;
  transition: ease-in-out 0.2s;
  opacity: 0;
  visibility: hidden;
  border-radius: 10px;
  padding: 10px 0;
}

.mobile-nav * {
  margin: 0;
  padding: 0;
  list-style: none;
}

.mobile-nav a {
  display: block;
  position: relative;
  color: #556270;
  padding: 10px 20px;
  font-weight: 500;
  outline: none;
}

.mobile-nav a:hover, .mobile-nav .active > a, .mobile-nav li:hover > a {
  color: #F8A50B ;
  text-decoration: none;
}

.mobile-nav .drop-down > a:after {
  content: "\ea99";
  font-family: IcoFont;
  padding-left: 10px;
  position: absolute;
  right: 15px;
}

.mobile-nav .active.drop-down > a:after {
  content: "\eaa1";
}

.mobile-nav .drop-down > a {
  padding-right: 35px;
}

.mobile-nav .drop-down ul {
  display: none;
  overflow: hidden;
}

.mobile-nav .drop-down li {
  padding-left: 20px;
}

.mobile-nav-overly {
  width: 100%;
  height: 100%;
  z-index: 9997;
  top: 0;
  left: 0;
  position: fixed;
  background: rgba(63, 73, 83, 0.6);
  overflow: hidden;
  display: none;
  transition: ease-in-out 0.2s;
}

.mobile-nav-active {
  overflow: hidden;
}

.mobile-nav-active .mobile-nav {
  opacity: 1;
  visibility: visible;
}

.mobile-nav-active .mobile-nav-toggle i {
  color: #fff;
}
</style>
