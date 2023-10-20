# 说明
node环境上传index.js,start.sh和package.json即可，容器平台需要docker部署的才上传Dockerfile

不需要自动访问可以注释掉index.js中第160行之后的部分，需要用的话。需要在index.js第三行填写项目url

第160行中的2为自动访问周期2分钟，根据个人需要修改

访问域名/list查看节点信息，默认账户：admin，默认密码：password

请在脚本运行完后2分钟内导出节点信息，list节点文件会在2分钟后删除，超过2分钟请读取sub.txt文件，域名/sub

glitch,replit,codesanbox均已测试ok

