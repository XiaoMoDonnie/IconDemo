# 图标库封装
 
预览地址: [https://XiaoMoDonnie.github.io/IconDemo/](https://okay-xiaomo.github.io/IconDemo/)

# 相关配置

 ``` <script>
        window.onload = function() {
            
            //初始化图标库
            var func = new FzIcons({
                container: '.fz-icons-modal-body', //图标库生成容器
                copyTipColor: '#ff80ab',           //复制成功提示颜色
                selectColor: '#ff80ab',            //图标选中的边框颜色
                pagingColor: '#ff80ab',            //分页器的颜色
                useClearBtn: true,                 //是否使用清空搜索按钮
                useDbClickCopy: true,              //是否使用双击复制
                pagingSize: 72                     //每页显示图标数量
            });

            //使用保存回调
            $("#Save").off('click').on('click', function() {
                console.log('save');
                // func.save(function(res) {
                //     console.log('通过save回调：' + res);
                // });
                console.log(func.save());
            });
        }
    </script> 
 ```
 
 [封装参考](https://www.cnblogs.com/jason1991/p/9177692.html)
 

