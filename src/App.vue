<script setup>
import HomepageBase from './components/Articles/HomepageBase.vue'
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
  <HomepageBase />
</template>
