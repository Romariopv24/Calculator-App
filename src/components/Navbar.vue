<template>
  <div class="navbar-container w-screen fixed bottom-0">
    <div class="navbar-content">
      <div class="icons flex justify-around text-slate-400">
        <a href="/casa">
        <i class='bx bx-home-alt bx-sm hover:text-orange-400 '></i>
        </a>
        <a href="/cesta">
        <i class='bx bxs-basket bx-sm hover:text-orange-400'></i>
        </a>
        <a href="/favoritos">
        <i class='bx bx-heart bx-sm hover:text-orange-400'></i>
        </a>
        <a href="/historial">
        <i class='bx bx-time-five bx-sm hover:text-orange-400'></i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >

</style>
