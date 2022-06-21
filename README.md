# 大事件项目 #
## 项目介绍 ##
* 该项目包括大事件项目的web服务器和api服务器
* api服务器连接mysql数据库（相关的数据结构需要自己查看定义）

## 项目运行 ##
1. 下载大事件文件夹
2. 查阅https://www.showdoc.cc/escook?page_id=3707158761215217，接口文档的数据结构，建立mysql数据库
3. 在`api_sercer/db/index.js`，链接自己的mysql服务器
4. 运行web服务器和api服务器`node app.js/web_server.js `