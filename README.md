#  **请移步到 https://github.com/beikeshop/beikeshop** 

***

## 软件架构
使用语言 PHP 8.1   
基于 Laravel 10 框架  
前端 Blade 模板 + Vue

## 环境要求
- 独立服务器(不能使用虚拟空间)
- CentOS 7.0+ 或 Ubuntu 20.04+
- PHP 8.1+
- MySQL 5.7+
- Apache httpd 2.4+ 或者 Nginx 1.10+

## PHP组件
- BCMath PHP Extension
- Ctype PHP Extension
- cURL PHP Extension
- DOM PHP Extension
- Fileinfo PHP Extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PCRE PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

## 安装教程(面向非开发者)
1. <a href="https://beikeshop.com/download" target="_blank">下载BeikeShop</a>
1. 上传到你的服务器并解压
1. 将解压文件夹下的 public 设置为网站根目录
1. 通过浏览器访问网站根据提示完成安装
1. <a href="https://docs.beikeshop.com/install/bt.html" target="_blank">BeikeShop详细安装指引</a>
1. 如需升级, 请下载最新版覆盖到服务器(必须保留原有.env文件), 然后在网站根目录运行`php artisan migrate`

## 安装教程(面向开发者)
1. 打开命令行克隆代码 `git clone https://gitee.com/beikeshop/beikeshop.git`
1. 命令行进入 `beikeshop` 目录, 执行 `composer install` 安装第三方包
1. 接着执行 `cp .env.example .env` 创建配置文件
1. 接着执行 `npm install`（node 版本需16+） 以及 `npm run prod` 编译前端 js 和 css 文件
1. 将项目文件夹下的 `public` 设置为网站根目录
1. 通过浏览器访问网站, 根据提示完成安装
1. 如需升级请在服务器端网站根目录运行`git pull && composer install && php artisan migrate`


