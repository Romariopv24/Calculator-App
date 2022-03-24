<template>
  <h2 class="font-extrabold m-6 text-2xl">Top Products</h2>
  <div class="scroll-content-top flex overflow-y-auto">
  <div class="top-products min-w-fit" :key="index" v-for="(item, index) in 10" >
    <div class="top-products-img w-40 m-6 ">
      <img src="https://media.istockphoto.com/photos/closeup-of-hamburger-with-black-background-picture-id1316673633?b=1&k=20&m=1316673633&s=170667a&w=0&h=4SUWvRqmq9eblMeMAksP_jL_J-fMUvnQUBHzfRClOZk=" alt="">
      
      <div class="top-products-text relative">
         <div class="top-products-title text-stone-700">
        Berry Juice
      </div>
        <div class="top-products-price text-orange-400">$7.5</div>
        <i class='bx bxs-plus-circle bx-sm bg-green-600 p-2 text-stone-50 rounded-full absolute bottom-0 right-0'>
        </i>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'TopProducts'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

