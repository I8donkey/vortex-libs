# vortex-libs
![License](https://img.shields.io/github/license/i8donkey/vortex-libs) ![Author](https://img.shields.io/badge/Author-i8doney-orange)
> English version：[readme](README.md)

这是一个为[vortex](https://www.github.com/i8doney/vortex)服务的项目，主要的作用为存储vortex的第三方库。

# 如何使用
1. 访问[releases](https://github.com/I8donkey/Vortex/releases)获取最新版vortex
2. 运行命令`git clone https://www.github.com/i8donkey/vortex-libs`
3. 按照以下的格式创作你的库：
```
vortex-libs/
    ...
    你的github用户名/
        ...
        你的库的名字/
            LICENSE
            lib.toml或者lib.json
```
lib.json:
```json
{
    "Name":...,
    "Author":...,
    "Version":...,
    "Description":"...",
    "Link":"https://www.github.com/xxx/xxx.git（也可以用其他的git平台）",
    "License":...
}
```
lib.toml:
```toml
Name = "..."
Author = "..."
Version = "..."
Description = "..."
Link = "https://www.github.com/xxx/xxx.git（同上）"
License = "..."
```
4. 将你的库推送到https://www.github.com/xxx/xxx.git
5. 发起PR