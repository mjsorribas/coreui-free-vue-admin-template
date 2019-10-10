<template>
  <b-card :header=headerData :class=classes :borderVariant=outlineColor :no-body="withRightCollapseIcon ? true : false" :v-if="withRightCollapseIcon ? 'show' : ''">
    <div v-if="!titleInFooter" slot="header">
      <i v-if="withIcon" :class=iconClass></i>
      {{title}}
      <div v-if="withActions" class="card-header-actions" style="height: 21px;">
        <c-switch v-if="withSwitch"  :size=switchSize :color=switchColor :checked=switchState label />
        <b-badge v-if="withLabel && !isLabelPill" :variant=labelColor >{{labelContent}}</b-badge>
        <b-badge v-if="withLabel && isLabelPill" pill :variant=labelColor>{{labelContent}}</b-badge>
        <b-link  v-if="withRightCustomLink" :href=rightCustomLink class="card-header-action btn-setting">
          <i class="icon-settings"></i>
        </b-link>
        <b-link  v-if="withRightCollapseIcon" class="card-header-action btn-minimize" v-b-toggle.collapse1>
          <i class="icon-arrow-up"></i>
        </b-link>
        <b-link  v-if="withRightCloseIcon" href="#" class="card-header-action btn-close" v-on:click="show = !show">
          <i class="icon-close"></i>
        </b-link>
      </div>
    </div>
    <b-collapse v-if="withRightCollapseIcon"  :id=collapseId visible>
       <b-card-body >
          {{content}}
       </b-card-body>
    </b-collapse>
    <div v-else>
      {{content}}
    </div>
    <div v-if="titleInFooter" slot="footer">{{title}}</div>
  </b-card>
</template>
<script>
import { Switch as cSwitch } from '@coreui/vue'
export default {
  name: 'Card',
  components: {
    cSwitch,
  },
  props:{
    classes:{
      type: String,
      required: false,
      default:''
    },
    headerData:{
      type: String,
      required: false,
      default:''
    },
    title:{
      type: String,
      required: true,
      default:'Title Card'
    },
    content:{
      type: String,
      required: true
    },
    titleInFooter:{
      type: Boolean,
      required: false,
      default: false
    },
    withActions:{
      type: Boolean,
      required: false,
      default: false
    },
    withSwitch:{
      type: Boolean,
      required: false,
      default: false
    },
    withLabel:{
      type: Boolean,
      required: false,
      default: false
    },
    withIcon:{
      type: Boolean,
      required: false,
      default: false
    },
    withOutline:{
      type: Boolean,
      required: false,
      default: false
    },
    withAccent:{
      type: Boolean,
      required: false,
      default: false
    },
    labelContent:{
      type: String,
      required: false,
      default: ''
    },
    labelColor:{
      type: String,
      required: false,
      default: 'primary'
    },
    isLabelPill:{
      type: Boolean,
      required: false,
      default: false
    },
    iconClass:{
      type: String,
      required: false,
      default: 'fa fa-check'
    },
    outlineColor:{
      type: String,
      required: false,
      default: ''
    },
    accentColor:{
      type: String,
      required: false,
      default: 'primary'
    },
    backgroundColor:{
      type: String,
      required: false,
      default: 'primary'
    },
    switchSize:{
      type: String,
      required: false,
      default: 'sm'
    },
    switchColor:{
      type: String,
      required: false,
      default: 'info'
    },
    switchState:{
      type: Boolean,
      required: false,
      default: false
    },
    withRightCustomLink:{
      type: Boolean,
      required: false,
      default: false
    },
    rightCustomLink:{
      type: String,
      required: false,
      default: '#'
    },
    withRightCollapseIcon:{
      type: Boolean,
      required: false,
      default: false
    },
    withRightCloseIcon:{
      type: Boolean,
      required: false,
      default: false
    },
    collapseId:{
      type: String,
      required: false,
      default: 'collapsed'
      },
  },
  data: function () {
    return {
      show: true
    }
  }
}
</script>
