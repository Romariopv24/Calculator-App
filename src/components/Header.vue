<template>
  <div class="home">
    <div class="header">
      <h2 class="title m-6 font-thin text-3xl">Hi<b class="font-extrabold"> Rom!</b></h2>
      <div class="input w-full flex relative items-center  ">
        <input class="w-10/12 bg-slate-50 border-0 outline-0 p-2.5 ml-5 rounded-2xl pl-12" type="text" placeholder="Find What you want...">
        <div class="icon-input absolute ml-8">
          <i class='bx bx-search-alt-2 bx-sm'></i>
        </div>
      </div>
      <div class="combo-header bg-green-600 text-white p-4 ml-6 w-10/12 rounded-3xl flex items-center mt-5">
      <div class="text w-2/4">
      <h3 class="font-bold text-lg">Free combo</h3>
      <p class="text-sm">Burger + Coca-cola for new users</p>
      </div>
      <div class="img w-2/4 object-cover">
      <img class="w-full rounded-lg" src="https://media.istockphoto.com/photos/cheesy-pepperoni-pizza-picture-id938742222?b=1&k=20&m=938742222&s=170667a&w=0&h=HyfY78AeiQM8vZbIea-iiGmNxHHuHD-PVVuHRvrCIj4=" alt="">
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
