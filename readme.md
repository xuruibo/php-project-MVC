项目结构：

统一入口文件
引入配置
引入类
自动加载类
根据参数自动跳转至控制器

C 控制器： 业务逻辑 负责跳转页面
M 模型类： 主要操作数据库，列表，详情，修改，添加等
V 试图： 负责显示数据

目录结构：
Common 公共文件
Lib 用到的类库
Controller 所有控制器
Model 所有模型
View 所有视图
index.php 项目入口

一般情况下， 一个表对应一个控制器可一个模型类，视图可能有很多个


![image](http://upload-images.jianshu.io/upload_images/1195879-f52b541ab2cfec0b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
