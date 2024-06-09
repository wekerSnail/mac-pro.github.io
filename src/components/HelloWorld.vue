<template>
  <div class="main-panel">
    <div>
      <img class="img" :src="macImg" alt="">
    </div>
    <div class="font-mini">深空黑色</div>
    <h2 class="text-left">
      11 核中央处理器<br />
      14 核图形处理器<br />
      18GB 统一内存<br />
      512GB 固态硬盘¹
    </h2>
    <div class="tip">
      14 英寸 Liquid 视网膜 XDR 显示屏²<br />
      三个雷雳 4 端口，以及 HDMI 端口、SDXC 卡插槽、耳机插孔和 MagSafe 3 端口<br />
      带有触控 ID 的妙控键盘<br />
      力度触控板<br />
      70W USB-C 电源适配器<br />
    </div>

    <h2 style="text-align: left;">
      Mac Pro数字兑换券
    </h2>
    <div class="font-mini">
      有限期至2099年12月31日
    </div>
    <button class="submit">兑换</button>
  </div>
</template>

<script setup>
import macImg from '../assets/mbp14-m3-max-pro-spaceblack-select-202310.jpg'
</script>

<style lang="scss" scoped>
.main-panel {
  background-color: #f5f5f7;
  border-radius: 18px;
  box-sizing: border-box;
  height: 100%;
  padding: 0 16px 20px;

  .img {
    height: auto;
    max-width: 100%;
    width: 280px;
  }

  .font-mini {
    color: #1d1d1f;
    font-size: 12px;
    text-align: left;
  }

  .text-left {
    text-align: left;
  }

  .tip {
    color: #1d1d1f;
    font-size: 14px;
    text-align: left;
  }
  .submit{
    background: #0076df;
    border-color: #0000;
    color: #fff;
    text-decoration: none;
    width: 100%;
    margin-top: 10px;
  }
}
</style>