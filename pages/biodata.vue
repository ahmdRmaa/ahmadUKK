<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-8">
        <div class="card">
          <div class="card-header bg-primary text-white text-center">
            <h4>Biodata saya</h4>
          </div>
          <div class="card-body">
            <div class="row">
              <div class="col-md-4">
                <img src="/assets/ahmad2.jpg" class="img-fluid rounded-circle" alt="Foto Profil" />
              </div>
              <div class="col-md-8">
                <h5>Nama Lengkap: <strong>Ahmad Rama Mauludin</strong></h5>
                <h5><strong>Alamat:</strong> Jl. Gobang Kp. Cintamanah</h5>
                <h5><strong>Email:</strong> ramahungkul36@gmail.com</h5>
                <h5><strong>No. Telepon:</strong> 085875941538</h5>
                <h5><strong>Hobi:</strong> memasak</h5>
                <h5><strong>Pendidikan:</strong> SMK NEGERI 4 TASIKMALAYA</h5>
              </div>
            </div>
          </div>
          <div class="card-footer text-center">
            <p>Terima kasih telah mengunjungi profil saya.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Biodata Pribadi",
    };
  },
};
</script>

<style scoped>
/* Anda dapat menambahkan styling tambahan di sini */
</style>
