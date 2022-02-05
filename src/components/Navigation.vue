<template>
  <div class="btns">
    <span class="item" @click="flyTo">DESERT</span>
    <!-- <span class="item">hill</span> -->
  </div>
</template>

<script setup lang="ts">

const flyTo = () => {
  window.open('https://rm.mainissues.cc', '_blank')
}

</script>

<style lang="scss" scoped>
  .btns {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 100%;

    .item {
      margin: 0 1rem;
      padding: .3rem 1.5rem .3rem .5rem;
      // padding-left: .5rem;
      // padding-right: 1.5rem;
      font-size: 1.4rem;
      display: inline-block;
      min-width: 4rem;
      text-align: center;
      border: 2px solid #ff0000;
      transition: all ease .5s;
      cursor: pointer;

      &:hover {
        color: #ff0000;
      }

      &:before {
        content: "";
        position: relative;
        width: 1rem;
        height: 3px;
        float: left;
        left: -1rem;
        border-bottom: 3px solid #ff0000;
        transition: all ease .5s;
        text-align: center;
        top: .6rem;
      }

      &:hover:before {
        left: calc(100% + 1rem);
      }
    }
  }
</style>