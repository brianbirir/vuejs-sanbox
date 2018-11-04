<template>
  <div id="app">
    <div class="page-header">
      <menu-bar></menu-bar>
      <h1>Risk Register</h1>
      <p class="lead">Kanban board example for Risk Register</p>
    </div>
    <router-view/>
  </div>
</template>

<script>

import MenuBar from '@/components/MenuBar'

export default {
  name: 'App',
  components: {
    'menu-bar': MenuBar
  }
}

</script>

<style>
  .page-header h1 {
    font-weight: 300;
  }

  .card {
    margin-bottom: 10px;
  }

  .card:last-child {
    margin-bottom: 25px;
  }

  .card-block {
    padding: 15px;
  }
</style>
