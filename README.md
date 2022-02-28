# motoko_deploy

Difinity课程第一节作业：

```bash
# 新建项目
dfx new motoko_deploy
# 进入项目文件夹
cd motoko_deploy/
# 为项目创建简单的html文件
echo '<html><body><h1>Hello World!</h1></body></html>' > src/mysite_assets/assets/index.html
# 启动本地环境
dfx start --background
# 部署项目到本地
dfx deploy
# 访问本地前端页面
http://ryjl3-tyaaa-aaaaa-aaaba-cai.localhost:8000
```