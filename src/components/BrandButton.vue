<template>
  <b-button :size=size :class=classes :variant=variant >
    <i v-if="icon" :class=icon ></i>
    <span v-if="title">{{title}}</span>
  </b-button>
</template>
<script>
export default {
  name: 'BrandButton',
  props:{
    size:{
      type: String,
      required: false,
      default:''
    },
    classes:{
      type: String,
      required: false,
      default:'mr-1 btn-brand'
    },
    title:{
      type: String,
      required: false,
      default: null
    },
    variant:{
      type: String,
      required: true,
      default:''
    },
    icon:{
      type: String,
      required: false,
      default:null
    },
  },
}
</script>
