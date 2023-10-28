<script setup>
import { ref } from 'vue'


const count = ref(0)
</script>

<template>
    <div class="mdui-table">
        <table class="table text-center">
            <thead>
                <tr>
                    <th style="width: 34%;"></th>
                    <th style="width: 22%;">原版VITS合成</th>
                    <th style="width: 22%;">Bert-VITS合成</th>
                    <th style="width: 22%;">MQTTS（自回归）合成</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th scope="row" class="text-start">合成是否快速</th>
                    <td>✓</td>
                    <td>✓</td>
                    <td></td>
                </tr>
                <tr>
                    <th scope="row" class="text-start">语调是否足够好</th>
                    <td></td>
                    <td>✓</td>
                    <td>✓</td>
                </tr>
            </tbody>

            <tbody>
                <tr>
                    <th scope="row" class="text-start">是否支持崩坏3合成</th>
                    <td>✓</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <th scope="row" class="text-start">是否高可用</th>
                    <td>✓</td>
                    <td>✓</td>
                    <td>✓</td>
                </tr>
                <tr>
                    <th scope="row" class="text-start">是否可以精细调整参数</th>
                    <td>✓</td>
                    <td>✓</td>
                    <td></td>
                </tr>
                <tr>
                    <th scope="row" class="text-start">是否支持原神/崩铁/未定角色合成</th>
                    <td>✓</td>
                    <td>✓</td>
                    <td>✓</td>
                </tr>
            </tbody>
        </table>
    </div>
</template>
