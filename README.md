## 基于 `Stylus` `xStyle` 的样式目录

- [bilibili-lite](bilibili-lite/README.md) 一个简化的bilibili页面样式，自适应黑暗模式
- [weibo-lite](weibo-lite/README.md) 一个简化的新浪微博页面样式，自适应黑暗模式
- [weibo-dark](weibo-lite/README.md) 为新版浪微博页页面样式增加自适应黑暗模式，支持设置为深色模式

## 其它说明

如果使用遇到问题，你可以优先 [查看帮助](./help.md)

你也可以加入交流QQ群 1061288553

![1061288553](https://i.loli.net/2020/03/28/agCTnyh2ZRDsQm3.jpg)

## 开发

``` sh
1. 全局安装 stylus

yarn global add stylus # or npm install -g stylus

2. 开发自动编译

yarn dev:bl # or npm run dev:bl  自动编译 bilibili-lite
yarn dev:wb # or npm run dev:wb  自动编译 weibo-lite
yarn dev:wd # or npm run dev:wd  自动编译 weibo-dark

3. 构建

yarn build # or npm run build  编译所有

yarn build:bl # or npm run build:bl  编译 bilibili-lite
yarn build:wb # or npm run build:wb  编译 weibo-lite
yarn build:wd # or npm run build:wd  编译 weibo-dark
```

> stylus 格式参考 .vscode-> settings.json
