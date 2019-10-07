<template>
  <div class="animated fadeIn">
    <b-row>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Title Card'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card footer'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=true
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with icon'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:withIcon=true
          v-bind:icon="'fa fa-check'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with switch'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:withActions=true
          v-bind:withSwitch=true
          v-bind:switchSize="'sm'"
          v-bind:switchColor="'info'"
          v-bind:switchState=false
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with label'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:withActions=true
          v-bind:withLabel=true
          v-bind:labelColor="'success'"
          v-bind:labelContent="'success'"
          v-bind:isLabelPill=false
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with label'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:withActions=true
          v-bind:withLabel=true
          v-bind:labelColor="'danger'"
          v-bind:labelContent="'42'"
          v-bind:isLabelPill=true
        />
      </b-col>
    </b-row><!--/.row-->
    <b-row>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card outline primary'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:outlineColor="'primary'"
          v-bind:headerData="'Card outline primary'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card outline secondary'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:outlineColor="'secondary'"
          v-bind:headerData="'Card outline secondary'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card outline success'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:outlineColor="'success'"
          v-bind:headerData="'Card outline success'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card outline info'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:outlineColor="'info'"
          v-bind:headerData="'Card outline info'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card outline warning'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:outlineColor="'warning'"
          v-bind:headerData="'Card outline warning'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card outline danger'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:outlineColor="'danger'"
          v-bind:headerData="'Card outline danger'"
        />
      </b-col>
    </b-row><!--/.row-->

    <b-row>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with primary accent'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with primary accent'"
          v-bind:classes="'card-accent-primary'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with secondary accent'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with secondary accent'"
          v-bind:classes="'card-accent-secondary'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with success accent'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with success accent'"
          v-bind:classes="'card-accent-success'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with info accent'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with info accent'"
          v-bind:classes="'card-accent-info'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with warning accent'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with warning accent'"
          v-bind:classes="'card-accent-warning'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card with danger accent'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with danger accent'"
          v-bind:classes="'card-accent-danger'"
        />
      </b-col>
    </b-row><!--/.row-->
    <b-row>
      <b-col sm="6" md="4">
        <b-card class="bg-primary text-center">
          <Blockquote
            v-bind:classes="'card-blockquote'"
            v-bind:content="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.'"
            v-bind:footerContent="'Someone famous in'"
            v-bind:citeContent="'Source Title'"
            v-bind:footerClasses="'blockquote-footer'"
          />
        </b-card>
      </b-col>
      <b-col sm="6" md="4">
        <b-card class="bg-success text-center">
          <Blockquote
            v-bind:classes="'card-blockquote'"
            v-bind:content="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.'"
            v-bind:footerContent="'Someone famous in'"
            v-bind:citeContent="'Source Title'"
            v-bind:footerClasses="'blockquote-footer'"
          />
        </b-card>
      </b-col>
      <b-col sm="6" md="4">
        <b-card class="bg-info text-center">
          <Blockquote
            v-bind:classes="'card-blockquote'"
            v-bind:content="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.'"
            v-bind:footerContent="'Someone famous in'"
            v-bind:citeContent="'Source Title'"
            v-bind:footerClasses="'blockquote-footer'"
          />
        </b-card>
      </b-col>
      <b-col sm="6" md="4">
        <b-card class="bg-warning text-center">
          <Blockquote
            v-bind:classes="'card-blockquote'"
            v-bind:content="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.'"
            v-bind:footerContent="'Someone famous in'"
            v-bind:citeContent="'Source Title'"
            v-bind:footerClasses="'blockquote-footer'"
          />
        </b-card>
      </b-col>
      <b-col sm="6" md="4">
        <b-card class="bg-danger text-center">
          <Blockquote
            v-bind:classes="'card-blockquote'"
            v-bind:content="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.'"
            v-bind:footerContent="'Someone famous in'"
            v-bind:citeContent="'Source Title'"
            v-bind:footerClasses="'blockquote-footer'"
          />
        </b-card>
      </b-col>
      <b-col sm="6" md="4">
        <b-card class="bg-secondary text-center">
          <Blockquote
            v-bind:classes="'card-blockquote'"
            v-bind:content="'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.'"
            v-bind:footerContent="'Someone famous in'"
            v-bind:citeContent="'Source Title'"
            v-bind:footerClasses="'blockquote-footer'"
          />
        </b-card>
      </b-col>
    </b-row><!--/.row-->
    <b-row>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card title'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card title'"
          v-bind:classes="'bg-primary'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card title'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card title'"
          v-bind:classes="'bg-success'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card title'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card title'"
          v-bind:classes="'bg-info'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card title'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card title'"
          v-bind:classes="'bg-warning'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <Card
          v-bind:title="'Card title'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card title'"
          v-bind:classes="'bg-danger'"
        />
      </b-col>
      <b-col sm="6" md="4">
        <transition name="fade">
        <Card
          v-bind:title="'Card with header actions'"
          v-bind:content="'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.'"
          v-bind:titleInFooter=false
          v-bind:headerData="'Card with header actions'"
          v-bind:classes="'bg-secondary'"
          v-bind:withActions=true
          v-bind:withRightCustomLink=true
          v-bind:linkCustom="'#'"
          v-bind:withRightCollapseIcon=true
          v-bind:withRightCloseIcon=true
          v-bind:collapseId="'collapsed1'"
        />
        </transition>
      </b-col>
    </b-row><!--/.row-->
  </div>
</template>

<script>
import { Switch as cSwitch } from '@coreui/vue'
import Blockquote from '../../components/Blockquote'
import Card from '../../components/Card'


export default {
  name: 'cards',
  components: {
    cSwitch,
    Blockquote,
    Card,
  },
  data: function () {
    return {
      show: true
    }
  }
}
</script>

<style scoped>
  .fade-enter-active {
    transition: all .3s ease;
  }
  .fade-leave-active {
    transition: all .8s cubic-bezier(1.0, 0.5, 0.8, 1.0);
  }
  .fade-enter, .fade-leave-to {
    transform: translateX(10px);
    opacity: 0;
  }
</style>
