# 用于记录vue a标签传多个参数

// 页面
<a :href="testClick(item.uuId,item.obId,item.type)" @click="learnNow()">立即学习</a>

// JS
testClick(val1,val2,val3) {
    return '/#/question/'+val1+'/'+val2+'/'+val3
}

// 跳转页面调用
obId: this.$route.params.obId,
