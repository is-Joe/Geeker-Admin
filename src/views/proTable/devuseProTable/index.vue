<template>
  <div class="table-box">
    <Protable :columns="columns" title="用户列表" ref="proTable">
      <template #toolButton>
        <el-button v-auth="'add'" type="primary"> 新增用户 </el-button>
      </template>
    </Protable>
  </div>
</template>

<script setup lang="tsx" name="dev_useProTable">
import Protable from "@/components/ProTable/index.vue";

const columns: [] = [];
</script>
