<template>
  <div>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">{{title}}</h5>
        <p class="card-text">
          {{desc}}
        </p>
        <a :href="link" class="btn btn-primary">Go somewhere</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    props: ["title","desc","link"]
};
</script>

<style>
</style>