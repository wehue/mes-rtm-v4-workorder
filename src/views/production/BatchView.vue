<template>
  <ModulePage
    module="生产调度"
    title="批次管理"
    description="围绕工单拆分批次、批次投产和状态查看展开，是生产调度到现场执行的连接点。"
    :cards="cards"
  />
</template>

<script setup>
import ModulePage from '../ModulePage.vue'

const cards = [
  { value: 'B001', title: '批次拆分', text: '把一个工单拆成多个可执行批次。' },
  { value: '待投产', title: '批次状态', text: '投产后进入上料、进站、出站流程。' },
  { value: '600', title: '批次数量', text: '用于后续演示数量流转。' },
]
</script>
