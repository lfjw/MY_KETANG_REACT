# MY课堂项目

分为前端和后端项目

前端使用react全家桶和Typescript

后端使用Node搭建服务

## 1. 初始化项目

生成一个typescript版本react项目
```sh 
create-react-app 项目名称 --typescript
```

## 2. 安装项目依赖

建议使用cnpm安装

```sh
cnpm i react-router-dom @types/react-router-dom react-transition-group @types/react-transition-group react-swipe @types/react-swipe antd qs @types/qs  -S
```

```sh
cnpm i redux react-redux @types/react-redux redux-thunk  redux-logger @types/redux-logger redux-promise @types/redux-promise immer redux-immer connected-react-router -S
```
```sh
cnpm i sass-loader node-sass -D
```
```sh
cnpm i px2rem-loader lib flexible -D
```
```sh
# 样式
cnpm i classnames -D
@types/classnames
```
```sh 
#轮播图
cnpm i React-Motion -S
```
## 3. UI组件

使用组件库
https://ant.design/


## 4. rem

- 设计稿正常是750px
- 量出来多少就多少写上，比方说100px,直接页面写100px

如何配置？

### 1 暴露出webpack配置文件
```sh
npm run eject
```

