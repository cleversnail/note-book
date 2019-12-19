# note-book
node+vue+mysql开发的一个全栈记事本


# 后端（note_book）

## 首先本地安装mysql，安装步骤自行官网或百度（我这里使用的是最新版的mysql，安装的时候会提示设置密码，使用老版本的小伙伴你们的密码默认是‘123456’）

## 然后将test.sql库倒入mysql，这是准备的一些测试假数据

## 搭建后端项目note_book（文件夹），使用koa-generator(koa的脚手架)快速创建一套koa后端项目模板（创建出来的目录结构请自行百度）

## 手动创建controllers文件夹，在其中创建defaultConfig.js（用来配置mysql参数）和mysqlConfig.js（用来定义mysql数据库查询方法）

## 具体逻辑请看代码


# 前端（front）

## 创建front项目，使用vue-cli快速创建vue项目模板（注：我这里使用的是vue2.0的语法）

## 前端vue项目使用了amfe-flexible（vue的rem）vant（ui框架，按需引入）axios（接口请求）


# clone之后

1. 保证你本地已经有mysql的情况下，将note_book > controllers > defaultConfig.js中的用户名和密码修改成你自己的

2. note_book下执行 npm install

3. note_book下执行 npm start

4. front目录下执行 npm install

5. front目录下执行 npm run dev

应该你已经看到效果了


