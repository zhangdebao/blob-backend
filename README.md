# Strapi application

A quick description of your strapi application

###  配置centen 服务器
yum install git
### 安装 nvm
- git clone git://github.com/creationix/nvm.git ~/nvm
- 验证安装
- - ```command -v nvm```
- 设置nvm自动运行
- - ```echo "source ~/nvm/nvm.sh" >> ~/.bashrc```
- - ```source ~/.bashrc```
- 查询Node.js版本
- 安装Node.js版本 ```nvm install v15.5.1```
- 切换Node.js版本 ```nvm use v15.5.1```
### SSH 秘钥配置登录配置
- MAC配置拷贝文件：cp -R ~/Downloads/zhangdb2021.pem ./

### 启动

npm run build
npm run start
## 持久存活 
pm2 start npm -- run start --name blog-backend

