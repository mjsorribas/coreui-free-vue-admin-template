<template>
  <div class="wrapper">
    <div class="animated fadeIn">
      <b-card
        header-tag="header"
        footer-tag="footer">
        <div slot="header">
          <i class="fa fa-align-justify"></i><strong> Bootstrap Pagination</strong>
          <div class="card-header-actions">
            <a href="https://bootstrap-vue.js.org/docs/components/pagination" class="card-header-action" rel="noreferrer noopener" target="_blank">
              <small class="text-muted">docs</small>
            </a>
          </div>
        </div>
        <div>
          <h6>Default</h6>
          <Pagination size="md" total="100" model="currentPage" perPage="10" />
          <br>

          <h6>Small</h6>
          <Pagination size="sm" total="100" model="currentPage" perPage="10" />
          <br>

          <div class="d-sm-down-none">
            <h6>Large</h6>
            <Pagination size="lg" total="100" model="currentPage" perPage="10" />
            <br>
          </div>

          <div>currentPage: {{currentPage}}</div>
        </div>
      </b-card>
      <b-card
        header-tag="header"
        footer-tag="footer">
        <div slot="header">
          <i class="fa fa-align-justify"></i><strong> Pagination </strong>
          <small>alignment</small>
        </div>
        <div>
          <h6>Left alignment (default)</h6>
            <Pagination  total="100" model="currentPage" perPage="10" />
          <br>

          <h6>Center alignment</h6>
          <Pagination  align="center" total="100" model="currentPage" perPage="10" />
          <br>

          <h6>Right (end) alignment</h6>
          <Pagination  align="right" total="100" model="currentPage" perPage="10" />
          <br>

          <div>currentPage: {{currentPage}}</div>
        </div>
      </b-card>
      <b-card
        header-tag="header"
        footer-tag="footer">
        <div slot="header">
          <i class="fa fa-align-justify"></i><strong> Pagination </strong>
          <small>navigation</small>
        </div>
        <div>
          <h6>Default</h6>
          <PaginationNav  base-url="#" numberOfPages="10" currentPage="currentPage" />
          <h6 class="mt-4">With link generator function</h6>
          <PaginationNav linkGen="linkGen" numberOfPages="10" currentPage="currentPage" />
          <br>
          <div class="mt-4">currentPage: {{currentPage}}</div>
        </div>
      </b-card>
    </div>
  </div>
</template>

<script>
import Pagination from '../../components/Pagination'
import PaginationNav from '../../components/PaginationNav'


export default {
  name: 'paginations',
  components: {
    Pagination,
    PaginationNav
  },  
  data () {
    return {
      currentPage: 3
    }
  },
  methods: {
    linkGen (pageNum) {
      return '#page/' + pageNum + '/foobar'
    }
  }
}
</script>

