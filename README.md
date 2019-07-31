# easy-dance-miniprogram

重写easy dance 微信小程序。

## 起步

- ### 推荐开发工具
  
  - [vscode](https://code.visualstudio.com/)
  可以去自行搜索一些插件集成

- ### 需要了解的
  
  - [Git命令行](https://www.git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%85%B3%E4%BA%8E%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6)

  - [React](https://www.reactjscn.com/)
  
  - [TypeScript](https://www.tslang.cn/)
  
  - [ES6](http://es6.ruanyifeng.com/)
  
  - [Taro](http://taro-docs.jd.com/taro/docs/README.html)

- ### 运行

> 需要安装[微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html),[Node.js](https://nodejs.org/zh-cn/)

开发环境(热更新，修改代码时在微信开发者工具可以随时查看效果)

```bash
npm run dev:weapp
```

生产环境（打包发布版本）

```bash
npm run build:weapp
```

输入以上指令会生成一个dist目录，可以在微信开发者工具中打开预览

## Quick Start

>为了代码（qiang）风格(po)统一(zheng)
配置了eslint与tslint 

```bash
npm i eslint tslint typescript -g
cd easydance-client/
tslint -c tslint.json
```
