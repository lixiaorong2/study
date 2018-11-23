<template>
    <div class="box">
        <div class="left_box"></div>
        <div class="center_box"></div>
        <div class="right_box"></div>
    </div>
</template>

<script>
export default {
  name: 'objectpk',
  data () {
    return {
    
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box{
    display: flex;
    height: 160px;
    flex-wrap: wrap;
    flex-grow: 1;
    align-items:center;
    margin: 10px 0px;
}
.left_box{
    width: 30%;
    height: 140px;
    border: 1px solid #ddd;
}
.center_box{
    width: 40%;
    height: 160px;
    border: 1px solid #ddd;
}
.right_box{
    width: 30%;
    height: 140px;
    border: 1px solid #ddd;
}
</style>
