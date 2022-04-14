## 基于 `Stylus` `xStyle` 的样式目录

- [bilibili-lite](bilibili-lite/README.md) 一个简化的bilibili页面样式，自适应黑暗模式
- [bilibili-palette](bilibili-palette/README.md) 为新版 bilibili 界面增加颜色配置，并增加深色模式
- [bilibili-core](bilibili-core/README.md) 简化新版 bilibili 页面样式，仅包括主站相关界面
- [weibo-lite](weibo-lite/README.md) 一个简化的新浪微博页面样式，自适应黑暗模式 (旧版本已废弃)
- [weibo-dark](weibo-dark/README.md) 为新版新浪微博页面增加深色模式 (待重构，仅提供颜色配置)

## 其它说明

如果使用遇到问题，你可以优先 [查看帮助](./help.md)

你也可以加入交流QQ群 1061288553

![1061288553](https://i.loli.net/2020/03/28/agCTnyh2ZRDsQm3.jpg)

## 开发

``` sh
# 1. 初始化

npm install

# 2. 开发自动编译

npm run dev:bl # 自动编译 bilibili-lite
npm run dev:bl # 自动编译 bilibili-palette
npm run dev:bl # 自动编译 bilibili-core
npm run dev:wb # 自动编译 weibo-lite
npm run dev:wd # 自动编译 weibo-dark

# 3. 构建

npm run build # 编译所有

npm run build:bl # 编译 bilibili-lite
npm run build:bl # 编译 bilibili-palette
npm run build:bl # 编译 bilibili-core
npm run build:wb # 编译 weibo-lite
npm run build:wd # 编译 weibo-dark
```

> stylus 格式参考 .vscode-> settings.json
