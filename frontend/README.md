# mandarin-library-automation 前端

基于Vue.js

## 环境配置

### 安装Node.js，换源

- 打开[Node.js官网](https://nodejs.org/en/)，选择LTS版本下载（目前为12.16.1），并进行安装。
- 使用淘宝源：`npm config set registry https://registry.npm.taobao.org`
- 验证换源是否成功：`npm config get registry`

### 安装vue-cli

- 安装：`npm install -g @vue/cli`
- 验证：`vue --version`

### 安装项目所需依赖

- 确保终端位于frontend目录内
- `npm install`来按照package.json安装所有所需依赖

### 进行本地测试

- 运行开发服务器：`npm run serve`
- 访问终端中显示的地址，应该能看到前端页面。
