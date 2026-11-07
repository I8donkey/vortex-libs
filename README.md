# vortex-libs
![License](https://img.shields.io/github/license/i8donkey/vortex-libs) ![Author](https://img.shields.io/badge/Author-i8doney-orange)
> Chinese version: [readme](README_zh.md)

This is a project serving [vortex](https://www.github.com/i8doney/vortex), whose main purpose is to store third-party libraries for vortex.

# How to use
1. Visit [releases](https://github.com/I8donkey/Vortex/releases) to get the latest version of vortex
2. Run the command `git clone https://www.github.com/i8donkey/vortex-libs`
3. Create your library according to the following format:
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
    "Link":"https://www.github.com/xxx/xxx.git (other git platforms work too)",
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
4. Push your library to https://www.github.com/xxx/xxx.git (following the format below)
```
src/
    main.vt
    xxx.vt
    ...
...
LICENSE
```
5. Open a PR