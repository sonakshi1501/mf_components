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
    props:{
            title:{
                type:String,
                required:true,
                default: "card title"
            },
            desc:{
                type:String,
                required:true,
                default: "card Description"
            },
            link:{
                type:String,
                required:true,
                default: "https://medium.com/techferment/7-data-flow-between-components-in-vue-js-3e2989aa27cd"
            }

        }
};
</script>

<style>
</style>