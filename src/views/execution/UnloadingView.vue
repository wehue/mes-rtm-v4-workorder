<template>
  <ModulePage
    module="生产执行"
    title="下料管理"
    description="上料操作的逆向纠正机制，支持将已上到工站的物料卸下并记录下料历史。"
    :cards="cards"
  />
</template>

<script setup>
import ModulePage from '../ModulePage.vue'

const cards = [
  { value: '待下料', title: '下料任务', text: '展示已上料但需要卸下的工站记录。' },
  { value: '扫码', title: '物料识别', text: '通过扫码选择需要下料的物料批次。' },
  { value: '记录', title: '下料记录', text: '保存下料信息，与上料记录联动追溯。' },
]
</script>
