<template>
  <button class="iota-donation-button" @click="count++">D {{ count }}</button>
</template>

<script>
export default {
  name: 'IotaDonationButton',
  data() {
    return {
      count: 0
    }
  }
}
</script>

<style scoped>
.iota-donation-button {
  position: absolute;
  top: 90%;
  left: 80%;
  display:block;
  height: 60px;
  width: 60px;
  background-color: #abcdef;
  color: white;
  font-size: 20px;
  border-radius: 50%;
  border: 1px solid #fedcba;
}

</style>