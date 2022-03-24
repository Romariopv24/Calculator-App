<template>
    <div class="scroll-menu  m-6">
      <div class="scroll-content-top flex overflow-y-auto ">
        <div class="avatar bg-slate-100 p-4 rounded-lg text-orange-400 m-1" :key="index" v-for="(item, index) in 10">
          <i class='bx bxs-pizza bx-sm' ></i>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'ScrollMenu',
  
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

