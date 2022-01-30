<template>
  <div class="dashboard-container">
    <el-row :gutter="24" class="login_from">
        <el-col class="login_tit">登录</el-col>
        <el-col :span="12" :offset="6">
            <el-form label-position="right" label-width="90px" :model="formLabelAlign">
                <el-form-item label="用户名">
                    <el-input v-model="formLabelAlign.userName"></el-input>
                </el-form-item>
                <el-form-item label="密码">
                    <el-input v-model="formLabelAlign.passWord"></el-input>
                </el-form-item>
                <el-button type="primary" @click="getUserRepositories">登录</el-button>
            </el-form>
        </el-col>
    </el-row>
  </div>
</template>

<script>

</script>