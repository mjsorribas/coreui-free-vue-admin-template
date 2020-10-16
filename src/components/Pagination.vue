<template>
    <b-pagination :align=align :size=size  :total-rows=total v-model=model :per-page=perPage >
    </b-pagination>
</template>
<script>
export default {
  name: 'Pagination',
  props:{
    align:{
      type: String,
      required: false,
      default:''
    },
    size:{
      type: String,
      required: false,
      default:''
    },
    total:{
      type: String,
      required: false,
      default:''
    },    
    model:{
      type: String,
      required: false,
      default:''
    },  
    perPage:{
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