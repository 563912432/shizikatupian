<template>
  <div class="footer">
    <div class="f-title">
      <span>本课程版权所有人为“哼哼成长”</span><span class="space">盗用必究</span>
    </div>
  </div>
</template>
<script>
export default {
  name: 'vfooter'
}
</script>
<style scoped>
  .footer {
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    height: 40px;
    font-size: 12px;
    background-color: #28AFF8;
    z-index: 1;
  }
  .footer .f-title{
    flex: 1;
    text-align: center;
    padding: 5px;
  }
</style>
