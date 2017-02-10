Crysadm+ 云端监控
=============
![image](https://github.com/hauntek/crysadm/raw/master/static/img/preview.png)

最新更新：2017-02-11
在线预览：http://www.crysadmapp.cn/guest

更新日记：2017-02-11
=============

1.优化项目更新脚本

2.优化前端更新流程

3.优化文件对比逻辑

4.修复更新导致系统根目录文件夹创建

5.修复检查更新缓存不删除问题

更新日记：2017-02-10
=============

1.添加更新程序，无限制平台

2.增加 检查及更新（在关于-更新历史）
- 按钮权限仅管理员可见，更新后默认会备份原有的

3.前端增加update文件监控

4.优化升级交互，添加实时反馈更新进度

5.修复开启备份后不更新问题

更新日记：2017-02-09
=============

1.修正后端速度循环统计

更新日记：2017-02-08
=============

1.添加 清除历史数据（在账号管理-我的个人信息）
- 删除全部监控历史记录数据 例如：历史速度，历史产量等 如果显示不出迅雷收益柱可以用这个方法解决

2.更新RSA加密函数，优化加密性能

更新日记：2017-01-29
=============

1.模板主题标题，右侧添加用户交流、加入群组按钮

2.调整关于页面排版问题

3.前端网站静态资源库(static)，更新INSPINIA 2.7底版

4.更换继承简洁模板(横向菜单)，依照INSPINIA 2.7模板调整

5.右上角添加当前动态时间

6.以及部分界面样式优化

更新日记：2016-12-05
=============

1.前端网站静态资源库(static)，更新INSPINIA 2.5底版

2.更新继承模板整体代码，依照INSPINIA 2.5模板调整

3.更新邮件小图标提示，添加收纳框

4.dashboard页面 方块间距调整，顺便添加宝箱收益

5.运行日记分页显示,支持标题筛选

6.添加页面加载动态条

7.以及部分界面样式优化

手动配置
=============

运行环境 python3.3+ , redis

crysadm 启动web服务

config 配置redis server

crysadm_helper 启动后台服务


安装后访问 /install 生成管理员账号

config.py.example 改名为config.py 使用
