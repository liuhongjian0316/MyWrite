# MyWrite

第一种（类似 v-if 控制）
$('a[data-toggle="tab"]').on('shown.bs.tab', function (e) {
            //获取激活标签
            var activeTab = $(e.target)[0].hash;
            //判断加载
            if(activeTab=="#tab-2") init();
});
第二种（官网）
$('a[data-toggle="tab"]').on('shown.bs.tab', function (e) {
            //获取激活标签
            var activeTab = $(e.target)[0].hash;
            //判断加载
            if(activeTab=="#tab-2") init1.resize();
 });
第三种
dispose 销毁之后 重新生成

第四种
重置样式 麻烦


