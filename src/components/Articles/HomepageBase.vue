<script setup>
import VersionList from './VersionList.vue'
import CompareVersion from './CompareVersion.vue'
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