<template>
  <div class="app-container">
    <el-table
      border
      fit
      highlight-current-row
    >
      <el-table-column label="ID" width="50" align="center">
        <template>
          ID
        </template>
      </el-table-column>
      <el-table-column label="Name" width="140" align="center">
        <template>
          Name
        </template>
      </el-table-column>
      <el-table-column label="Description" width="300" align="center">
        <template>
          Description
        </template>
      </el-table-column>
      <el-table-column label="Artists" width="100" align="center">
        <template>
          Artists
        </template>
      </el-table-column>
      <el-table-column label="Image URL" width="300" align="center">
        <template>
          Image URL
        </template>
      </el-table-column>
      <el-table-column label="Controls" align="center">
        <template>
          Controls
        </template>
      </el-table-column>
    </el-table>
  </div>
</template>

<script>

export default {}
</script>
