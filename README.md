# generator-loopback-vue ``热更新,热部署 典型前后端分离项目模板``
[![License][license-img]][license-url]
[![NPM Version][npm-img]][npm-url]
[![Node Version][node-image]][node-url]
[![Build Status][travis-img]][travis-url]
[![Downloads][downloads-image]][downloads-url]
[![Dependency Status][david-img]][david-url]

[![NPM](https://nodei.co/npm/generator-loopback-vue.png?downloads=true&stars=true)](https://nodei.co/npm/generator-loopback-vue/)

[travis-img]: https://travis-ci.org/qxl1231/generator-loopback-vue.svg?branch=master
[travis-url]: https://travis-ci.org/qxl1231/generator-loopback-vue
[npm-img]: https://img.shields.io/npm/v/generator-loopback-vue.svg
[npm-url]: https://npmjs.org/package/generator-loopback-vue
[david-img]: https://img.shields.io/david/qxl1231/generator-loopback-vue.svg
[david-url]: https://david-dm.org/qxl1231/generator-loopback-vue
[downloads-image]: https://img.shields.io/npm/dm/generator-loopback-vue.svg
[downloads-url]: https://npmjs.org/package/generator-loopback-vue
[license-img]: http://img.shields.io/badge/license-MIT-green.svg
[license-url]: http://opensource.org/licenses/MIT
[node-image]: https://img.shields.io/badge/node.js-v4.0.0-blue.svg
[node-url]: http://nodejs.org/download/


## 通过本源码你可以学习到:(loopback中国讨论组-群号:575600225)
- Strongloop是是如何通过一行命令和代码实现restful API接口,包括CRUD等14个接口
- model是如何定义的,以及model-relation 定义,以及ACL接口权限控制等
- CI持续集成的配置,Docker容器,docker部署文件
- **如何登录鉴权,以及接口权限控制**
- vue1.0 是如何玩?以及vue-resouce的使用,vue-router,webpack,babel等
- loopback自带的authenticate 权限控制,accesstoken机制,credentials
- strong-pm 部署命令,以及slc主要命令
- 如何把项目部署在daocloud中,以及集成daovoice服务
- ***增加了个vue-pagenav 组件的使用 实现分页功能***


## Docker镜像 ,在daocloud.io中
最新版本: latest
镜像地址: daocloud.io/qxl1231/lb-vue2

## 在线demo:
> http://loopback-vue.daoapp.io/
`帐号:test,密码:testpwd`

## 部分截图
![image](https://cloud.githubusercontent.com/assets/8305742/17387903/810c8b16-5a2a-11e6-862a-9306067bfc34.png)
> 集成了daovoice玩玩哈哈~~~炫酷!
![image](./daovoice.png)

![image](https://cloud.githubusercontent.com/assets/8305742/17387949/dce5d7d0-5a2a-11e6-9e1d-5fe93b2924b2.png)

The project is generated by [LoopBack](http://loopback.io).+[vue.js](http://vuejs.org).

## 如何启动:(国内用cnpm(先运行npm i cnpm -g),国外用npm)
```   
       1. npm i   
       2. 修改datasources.json 中的数据库配置比如:localhost:27017
       3. node server/bin/create-admin.js 添加管理员帐号,密码
       3.npm run build:js & node .(cold reload) --hot reload npm run watch:js
```

## 遇到问题1:loopback+vue 不能运行
答:1.npm install   2.npm run build:js  3.node .

## 问题2:热部署
To use hot reload, please try this command:npm run watch:js & node .

## 热启动:$npm run watch:js & node .

 
## 问题3:If you have error, try this:
回答:
` npm install
  vueify-insert-css vue-hot-reload-api
  babel-core babel-preset-es2015
  babel-plugin-transform-runtime babel-runtime@5
  --save-dev `
 
  
## Hot reloading detail: 
https://github.com/vuejs/vueify

## 其他help===>loopback 常用命令行:
 - slc loopback 初始化项目
 - slc loopback:datasource
 - slc loopback:model
 - slc loopback:relation
 - slc loopback boot-script


## others:deploy and status

 - slc deploy http://usr:pwd@localhost:port  
 - slpmctl -C http://usr:pwd@localhost:8701 ls   

 - slpmctl -C http://usr:pwd@domain:8701 status 

 - pm2 start -n weather app.js

 - pm2 start -n app_update_server server.js

## LICENSE

MIT



## 捐赠
| No        | ID           | github  |
| ------------- |:-------------:| -----:|
| 1     | JLF | https://github.com/cnJLF |
| 2      | you      |    |
| 3 | are next      |     |

> ❤❤❤❤感谢我的兄弟们大力支持❤❤❤❤❤❤:
- No.1    [JLF]:https://github.com/cnJLF



![支付宝](./alipay.jpeg) | ![微信](./Wechat.jpeg)
