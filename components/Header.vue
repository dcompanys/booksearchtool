<template>
  <div>
    <header class="bg-primary bg-text-white p-lg-5">
      <div class="row">
        <div class="col-lg-1">
        </div>
        <div class="col-lg">
          <img src="~/assets/img/logo1.png" alt="logo1" />
        </div>
        <div class="col-lg">
          <h1>Perpustakaan</h1>
          <div>SMKN 4 Tasikmalaya</div>
          <address>Jl.Depok, Sukamenak, Purbaratu 46196</address>
        </div>
      </div>
    </header>
    <slot />
  </div>
</template>

<style scoped>
.logo {
  width: 90px;
}
</style>