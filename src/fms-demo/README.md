#Front Mock Server | 前端数据模拟服务器

https://github.com/nimojs/fms/


##使用感受：
1. 生成API接口文档：访问虚拟数据服务器根路径，能看到全部的虚拟数据的API接口详情  
2. 在服务器根，能操作接口返回成功或失败  
3. 编辑API的数据，页面能实时得到新的数据  


其他：
1. 注意，官方文档说明，使用nodemon运行fms，才实时修改接口，实时查看效果，否则可能需要手动重启fms才能看效果。
2. fms v 0.0.28 暂未支持跨域访问api（后面我提交代码过去了，0.0.29 已实现跨域）


##此fms-demo，怎么用？
在此目录下，运行命令安装依赖的模块：
```
npm i
```
运行项目：
```
npm start
```
打开浏览器，进入对应url，就能看到对应的效果了。


