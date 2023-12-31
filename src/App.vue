<script setup>
import VersionList from './components/Articles/VersionList.vue'
import CompareVersion from './components/Articles/CompareVersion.vue'
import 'mdui/mdui.css';
import 'mdui';
import 'mdui/components/top-app-bar.js';
import 'mdui/components/top-app-bar-title.js';
import 'mdui/components/icon.js';
import '@mdui/icons/search.js';
import 'mdui/components/layout.js';
import 'mdui/components/layout-item.js';
import 'mdui/components/layout-main.js';
import { setColorScheme } from 'mdui/functions/setColorScheme.js';

// 根据 #0061a4 生成一套配色方案，并将 <html> 设置为该配色方案
setColorScheme('#0061a4');
</script>

<template>
  <mdui-layout>
  <mdui-top-app-bar>
    <mdui-top-app-bar-title>原神在线TTS</mdui-top-app-bar-title>
  </mdui-top-app-bar>
  <mdui-layout-main style="min-height: 300px;">

  <div class="mdui-prose container">
    <h1>目前可用的版本</h1>
    <VersionList />
    <br />
    <h1>版本功能对比</h1>
    <CompareVersion />
    <p>© 2023 Stardust·减</p>
  </div>
</mdui-layout-main>
</mdui-layout>
</template>

<style scoped>
.container {
  padding: 1rem 1rem;
}
</style>
