<template>

</template>

<script>
export default {
  data () {
    return {
        arr:[
            {isUrgent: "0", personnel: "张三", sex: "1", address: "1", edit: "0", remark: "备注"},
            {isUrgent: "1", personnel: "李四", sex: "1", address: "2", edit: "1", remark: ""},
            {isUrgent: "0", personnel: "王五", sex: "1", address: "2", edit: "0", remark: ""},
            {isUrgent: "0", personnel: "赵六", sex: "1", address: "3", edit: "0", remark: "123"},
            {isUrgent: "0", personnel: "赵六", sex: "2", address: "4", edit: "1", remark: ""},
            {isUrgent: "1", personnel: "王五", sex: "2", address: "1", edit: "0", remark: ""},
            {isUrgent: "1", personnel: "李四", sex: "2", address: "3", edit: "0", remark: "222222"},
            {isUrgent: "1", personnel: "张三", sex: "2", address: "4", edit: "0", remark: " "},
        ],
        address:[
          {code:1,word:"北京"},
          {code:2,word:"天津"},
          {code:3,word:"上海"},
          {code:4,word:"广州"},
        ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
