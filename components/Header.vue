<template>
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
      <img src="~/assets/LOGO-SMK4.png" style="width: 3%" alt="" />
      <a class="navbar-brand fw-bold" >SMK NEGERI 4 Tasikmalaya</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <ul class="navbar-nav mx-5 pt-2">
            <li class="nav-item">
              <nuxt-link to="/">
                <h6>HOME</h6>
              </nuxt-link>
            </li>
            <li class="nav-item dropdown mx-3">
              <h6
                class="dropdown-toggle"
                id="navbarDropdownMenuLink"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                PROFILE
              </h6>
              <ul
                class="dropdown-menu text-dark"
                aria-labelledby="navbarDropdownMenuLink"
              >
                <li>
                  <nuxt-link to="/sejarah"
                    ><div class="dropdown-item">Sejarah</div></nuxt-link
                  >
                </li>
                <li>
                  <nuxt-link to="/visi"
                    ><div class="dropdown-item">Visi & Misi</div></nuxt-link
                  >
                </li>
              </ul>
            </li>
            <li class="nav-item mx-3">
              <nuxt-link to="/ekskul">
                <h6>EKSTRAKULIKULER</h6>
              </nuxt-link>
            </li>
            <li class="nav-item mx-3">
              <nuxt-link to="/galeri">
                <h6>GALERI</h6>
              </nuxt-link>
            </li>
          </ul>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.nav-item,
h6 {
  color: black;
}
</style>
