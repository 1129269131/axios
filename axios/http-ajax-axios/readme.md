# 项目调试说明：test目录下的html文件直接使用浏览器打开即可开始测试（以下两个工具选择其一作为服务器启动）

# json-server（用来快速搭建REST API的工具包）使用指南
1、使用Visual Studio Code软件打开该项目
2、npm install -g json-server（若未安装时需要安装）
3、在Visual Studio Code终端运行命令启动json-server： json-server --watch db.json
报错解决方法（在此系统上禁止运行脚本）：https://blog.csdn.net/Q_do_it/article/details/107785076
github地址：https://github.com/typicode/json-server
4、访问http://localhost:3000，可以打开即成功

# server.js使用指南（03_axios3_cancel_day05.html、03_axios3_cancel_day06.html、03_axios3_cancel_day07.html中使用到）
1、使用Visual Studio Code软件打开该项目
2、在Visual Studio Code终端运行命令启动server.js：node server.js