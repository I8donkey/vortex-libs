# vortex-libs
![License](https://img.shields.io/github/license/i8donkey/vortex-libs) ![Author](https://img.shields.io/badge/Author-i8doney-orange)
> 简体中文版见：[中文文档](README_zh.md)

This repository supports [vortex](https://www.github.com/i8doney/vortex) by hosting its third-party libraries.

# How to use
1. Go to [releases](https://github.com/I8donkey/Vortex/releases) and download the latest version of vortex.
2. Run `git clone https://www.github.com/i8donkey/vortex-libs`
3. Add your library using the following layout:
```
vortex-libs/
    ...
    your-github-username/
        ...
        your-library-name/
            LICENSE
            lib.toml or lib.json
```
lib.json:
```json
{
    "Name":...,
    "Author":...,
    "Version":...,
    "Description":"...",
    "Link":"https://www.github.com/xxx/xxx.git (other Git platforms are also supported)",
    "License":...
}
```
lib.toml:
```toml
Name = "..."
Author = "..."
Version = "..."
Description = "..."
Link = "https://www.github.com/xxx/xxx.git (same as above)"
License = "..."
```
4. push your lib to https://www.github.com/xxx/xxx.git
5. Open a pull request.