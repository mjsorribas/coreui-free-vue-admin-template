<template>
  <div class="wrapper">
    <div class="animated fadeIn">
      <b-row>
        <b-col>
          <b-card
            header-tag="header"
            footer-tag="footer">
            <div slot="header">
              <i class="fa fa-align-justify"></i> <strong> Bootstrap Jumbotron </strong>
              <div class="card-header-actions">
                <a href="https://bootstrap-vue.js.org/docs/components/jumbotron" class="card-header-action" rel="noreferrer noopener" target="_blank">
                  <small class="text-muted">docs</small>
                </a>
              </div>
            </div>
            <div>
              <Jumbotron
                  v-bind:headerData="'Bootstrap 4'"
                  v-bind:classes="'Bootstrap 4 Components for Vue.js 2'"
                  v-bind:leadData="'Title Card'"
                  v-bind:content="'For more information visit website.'"
                  v-bind:withButton="true"
                  v-bind:buttonSize="sm"
                  v-bind:buttonClasses="btn"
                  v-bind:buttonVariant="primary"
                  v-bind:buttonText="'More Info'"
                  v-bind:buttonLink="'#'"
                  
                />
            </div>
          </b-card>
        </b-col>
        <b-col>
          <b-card
            header-tag="header"
            footer-tag="footer">
            <div slot="header">
              <i class="fa fa-align-justify"></i> <strong> Jumbotron </strong>
              <small>with slots</small>
            </div>
            <div>
              <b-jumbotron>
                <template slot="header">
                  Bootstrap 4
                </template>
                <template slot="lead">
                  This is a simple hero unit, a simple jumbotron-style component for
                  calling extra attention to featured content or information.
                </template>
                <hr class="my-4">
                <p>
                  It uses utility classes for typography and spacing to space content
                  out within the larger container.
                </p>
                <b-btn variant="primary" href="#">Do Something</b-btn>
                <b-btn variant="success" href="#">Do Something Else</b-btn>
              </b-jumbotron>
            </div>
          </b-card>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <b-card
            header-tag="header"
            footer-tag="footer">
            <div slot="header">
              <i class="fa fa-align-justify"></i> <strong> Jumbotron </strong>
              <small>variants</small>
            </div>
            <div>
              <b-jumbotron bg-variant="info" text-variant="white" border-variant="dark">
                <template slot="header">
                  Bootstrap 4
                </template>
                <template slot="lead">
                  This is a simple hero unit, a simple jumbotron-style component for
                  calling extra attention to featured content or information.
                </template>
                <hr class="my-4">
                <p>
                  It uses utility classes for typography and spacing to space content
                  out within the larger container.
                </p>
              </b-jumbotron>
            </div>
          </b-card>
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
import Jumbotron from '../../components/Jumbotron'

export default {
  name: 'jumbotrons',
   components: {
    Jumbotron
  },
 data: function () {
    return {
      show: true
    }
  }  
}
</script>

