<script setup>
import { ref } from 'vue'


const count = ref(0)
</script>

<template>
<div class="card">
    <mdui-card class="sigle-card">
      <h3>原版VITS合成 3.8</h3>支持崩坏3语音合成<br>需要多次抽卡合成<br>语调可能会乱飞<br>合成最快<br><br><mdui-button href="https://genshinvoice.top/v1/" target="_blank">点击进入</mdui-button>
    </mdui-card>
    <mdui-card class="sigle-card">
      <h3>Bert-VITS2合成 4.0</h3>支持枫丹！<br>支持调整SDP Ratio,使用VITS2 Backbone<br>语调相对较好<br>合成次快<br><br><mdui-button href="https://genshinvoice.top/v2/" target="_blank">点击进入</mdui-button>
    </mdui-card>
    <mdui-card class="sigle-card">
      <h3>MQTTS（自回归）合成--暂不可用 3.8</h3>不支持崩坏3语音合成<br>不支持调整参数<br>语调有绝对优势<br>合成极慢<br><br><mdui-button href="https://genshinvoice.top/v3/" target="_blank">点击进入</mdui-button>
    </mdui-card>
    </div>
</template>

<style scoped>
.card {
  text-align: center;
  width: auto;
  height: auto;
}

.sigle-card {
  margin-left: 1rem;
  margin-right: 1rem;
}
</style>