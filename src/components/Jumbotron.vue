<template>
  <b-jumbotron :header=headerData :class=classes :lead=leadData >
    <p>{{content}}</p>
    <b-button :v-if="withButton" :size=buttonSize :class=buttonClasses :variant=buttonVariant >
    </b-button>
  </b-jumbotron>
</template>
<script>
export default {
  name: 'Jumbotron',
  props:{
    classes:{
      type: String,
      required: false,
      default:'jumbotron'
    },
    header:{
      type: String,
      required: false,
      default:''
    },
    leadData:{
      type: String,
      required: false,
      default:''
    },    
    content:{
      type: String,
      required: false,
      default:''
    },      
    withButton:{
      type: Boolean,
      required: false,
      default:false
    },
    buttonSize:{
      type: String,
      required: false,
      default:''
    }, 
    buttonClasses:{
      type: String,
      required: false,
      default:'btn'
    },
    buttonVariant:{
      type: String,
      required: false,
      default:'primary'
    },        
  },
  data: function () {
    return {
      show: true
    }
  }
}
</script>