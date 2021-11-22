<template>
  <div>
    <h1>hello world commaeng</h1>
  </div>
  <div class="row">
    <div class="w-33">
      <h1>{{textName}}</h1>
    </div>
    <div class="w-33">
      <h1>{{box}}</h1>
    </div>
    <div class="w-33">
      <h1>{{textName}}</h1>
    </div>  
  </div>
</template>

<script>
export default {  
  setup() {
    const textName="commaeng"
    const box="ddd"
    return{
      textName,
      box
    }
  }
}
</script>

<style>
.row {
  display: flex;
}
.w-33{
  width: 33.33%;
  background-color: brown;
  margin: 10px 10px;
}
</style>