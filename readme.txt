1.下载并安装node.js

2.启动cmd,用cd命令进入到目录 nodejs_socketio_chat/server

3.安装express,socket.io:
  npm install --save express
  npm install --save socket.io

4.启动server/index.js:node index.js;
成功会输出listening on *:3000
浏览器打开http://localhost:3000地址，看到欢迎页面。

5.window环境下，打开IIS，建立客户端站点，然后访问即可。
路径：nodejs_socketio_chat\client\
注意端口不要和服务器的冲突。

