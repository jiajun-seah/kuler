<template>
      <div id="banner-searchResults">
        <img src="@/assets/banner-Results.jpg" 
        alt="Banner" class="img-fluid">
    </div>
  <div class="container pt-5" div="details">
  <div class="row">
    <div class="col-lg-2">
      <FilterOptions/>
    </div>
    <div class="col-lg-10">
      <ProductCard/>
    </div>
  </div>
</div>
  <div>
  </div>
</template>
<style>
.work-page {
  width: 80vmax;
  margin-left: auto;
}
#banner-searchResults img{
  width: 100%;
  height: 20vh;
}
</style>

<script>
import FilterOptions from '@/components/FilterOptions.vue'
import ProductCard from '@/components/ProductCard.vue'

export default {
  name: 'App',
  components:{
    FilterOptions,
    ProductCard
  },
  data(){
    
  },
  methods:{
   
  }
}
</script>
