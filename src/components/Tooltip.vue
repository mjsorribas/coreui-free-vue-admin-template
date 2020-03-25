<template>
  <div :class=containerClasses>
    <b-btn :id=buttonId :variant=buttonVariant>{{buttonText}}</b-btn>
    <b-tooltip :ref=ref :target=target :placement=placement :title=title>
      {{content}}
    </b-tooltip>
  </div>
</template>
<script>
export default {
  name: 'Tooltip',
  props:{
    containerClasses:{
      type: String,
      required: false,
      default:''
    },
    buttonId:{
      type: String,
      required: true,
    },
    buttonVariant:{
      type: String,
      required: false,
      default:'primary'
    },
    buttonText:{
      type: String,
      required: false,
      default:'Button'
    },
    content:{
      type: String,
      required: true,
    },
    target:{
      type: String,
      required: true,
    },
    action:{
        type:String,
        required:false,
    },
    placement:{
        type:String,
        required:true,
    },
    ref:{
        type:String,
        required:false,
    },
    title:{
        type:String,
        required:false,
    }
  }
}
</script>
