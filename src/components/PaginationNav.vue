<template>
     <b-pagination-nav :align=align :base-url=baseUrl :link-gen=linkGen :number-of-pages=numberOfPages :v-model=currentPage />
</template>
<script>
export default {
  name: 'Pagination-nav',
  props:{
    align:{
      type: String,
      required: false,
      default:''
    },
    totalRows:{
      type: String,
      required: false,
      default:''
    },
    numberOfPages:{
      type: String,
      required: false,
      default:''
    },    
    currentPage:{
      type: String,
      required: false,
      default:''
    },              
  },
  data: function () {
    return {
      show: true
    }
  }
}
</script>