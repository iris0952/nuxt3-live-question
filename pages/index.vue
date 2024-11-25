<script setup></script>

<template>
  <div>
    <h1>首頁</h1>
    <h3>測試字體</h3>
    <p class="title">標題</p>
    <button type="button" class="btn btn-primary">Primary</button>
    <button type="button" class="btn btn-secondary">Secondary</button>
    <button type="button" class="btn btn-success">Success</button>
    <button type="button" class="btn btn-danger">Danger</button>
    <button type="button" class="btn btn-warning">Warning</button>
    <button type="button" class="btn btn-info">Info</button>
    <button type="button" class="btn btn-light">Light</button>
    <button type="button" class="btn btn-dark">Dark</button>
    <button type="button" class="btn btn-link">Link</button>
  </div>
</template>

<style lang="scss">

h1{
  color: $primary;
}
h3{
  color: $indigo;
}
button.btn{
  cursor: pointer;
  margin-right: 10px;
}
</style>
