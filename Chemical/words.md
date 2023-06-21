# 生词对照表
<script setup lang="ts">
import {NDataTable}from 'naive-ui'
import type { DataTableColumns } from 'naive-ui'
const data = [
  {'en':'Quadratics','cn':'二次方程'},
]
const columns:DataTableColumns=[{
    title: '英语',
    key: 'en',
    align:'center'
},{
    title: '中文',
    key: 'cn',
    align:'center'
}]
</script>
 <n-data-table
    :columns="columns"
    :data="data"
  />



