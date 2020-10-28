<template>
    <b-progress class="classes"  :value="counter" :max="max" :show-progress :animated :show-value :variant="variant"></b-progress>

</template>
<script>
export default {
 name: 'ProgressBar',
  props:{
    align:{
      type: String,
      required: false,
      default:''
    },
    classes:{
      type: String,
      required: false,
      default:''
    },
    value:{
      type: Number,
      required: false,
      default:''
    },    
    counter:{
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
    
}
</script>