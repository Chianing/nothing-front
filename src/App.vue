<template>
    <div>
        <el-container>
            <el-header>
                <navigation-header/>
            </el-header>

            <el-container>
                <el-aside width="200px">
                    <navigation-left/>
                </el-aside>

                <el-main>Main</el-main>
            </el-container>
        </el-container>
    </div>
</template>

<script>

import NavigationHeader from "@/components/common/NavigationHeader";
import NavigationLeft from "@/components/common/NavigationLeft";

export default {
    name: 'App',
    components: {
        NavigationLeft,
        NavigationHeader
    }
}
</script>

<style>

</style>
