### 1.设置要比较的2个文件路径
要求：
- 表格的格式一样
- 表名不能一样，因为不能同时打开2个名字相关的文件

### 2.生成的差异表格
- sheet名字是之前的名字+"_diff",如之前的表格是apk，生成的差异sheet名字叫apk_diff
- 生成的列格式如下

![demo](https://github.com/chadmXiang/CompareExcel/blob/master/picture/demo.png?raw=true)

### 3.设置刷新的间隔时间
打开开发工具，可以设置时间
```
delayTime (0.15)  '间隔时间单位是秒，此处是0.15S
```
![vba](https://github.com/chadmXiang/CompareExcel/blob/master/picture/vba.png?raw=true)



