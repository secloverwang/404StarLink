## HackBrowserData <https://github.com/moonD4rk/HackBrowserData>
<!--auto_detail_badge_begin_0b490ffb61b26b45de3ea5d7dd8a582e-->
![Language](https://img.shields.io/badge/Language-Golang-blue)
![Author](https://img.shields.io/badge/Author-moonD4rk-orange)
![GitHub stars](https://img.shields.io/github/stars/moonD4rk/HackBrowserData.svg?style=flat&logo=github)
![Version](https://img.shields.io/badge/Version-V0.4.2-red)
![Time](https://img.shields.io/badge/Join-20201221-green)
<!--auto_detail_badge_end_fef74f2d7ea73fcc43ff78e05b1e7451-->

<div align="center">
<img src="https://github.com/moonD4rk/HackBrowserData/raw/master/LOGO.svg" alt="hack-browser-data logo" />
</div>

`HackBrowserData` 是一个浏览器数据（密码|历史记录|Cookie|书签|信用卡|下载记录|localStorage|浏览器插件）的导出工具，支持全平台主流浏览器。


> 免责声明：此工具仅限于安全研究，用户承担因使用此工具而导致的所有法律和相关责任！作者不承担任何法律责任！

## 各平台浏览器支持情况

### Windows

| 浏览器        | 密码 | Cookie | 书签 | 历史记录 |
| :------- | :------: | :----: | :------: | :-----: |
| Google Chrome|    ✅     |   ✅    |    ✅     |    ✅    |
| Google Chrome Beta|    ✅    |   ✅   |    ✅    |    ✅    |
| Chromium |    ✅    |    ✅    |    ✅    |    ✅    |
| Microsoft Edge|    ✅     |   ✅    |    ✅     |    ✅    |
| 360 极速浏览器    |    ✅     |   ✅    |    ✅     |    ✅    |
| QQ |    ✅     |   ✅    |    ✅     |    ✅    |
| Brave  |    ✅    |   ✅   |    ✅    |    ✅    |
| Opera  |    ✅    |    ✅    |    ✅    |    ✅    |
| OperaGX  |    ✅    |    ✅    |    ✅    |    ✅    |
| Vivaldi  |    ✅    |    ✅    |    ✅    |    ✅    |
| Yandex |    ✅    |    ✅    |    ✅    |    ✅    |
| CocCoc |    ✅    |    ✅    |    ✅    |    ✅    |
| Firefox |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Dev |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox ESR |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Nightly |    ✅    |   ✅   |    ✅    |    ✅    |
| IE 浏览器        |    ❌     |   ❌    |    ❌     |    ❌    |

### MacOS

由于 MacOS 的安全性设置，基于 `Chromium` 内核浏览器解密时**需要当前用户密码**

| 浏览器    | 密码 | Cookie | 书签 | 历史记录 |
| :--- | :------: | :----: | :------: | :-----: |
| Google Chrome  |    ✅     |   ✅    |    ✅     |    ✅    |
| Google Chrome Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Chromium |    ✅    |    ✅    |    ✅    |    ✅    |
| Microsoft Edge |    ✅     |   ✅    |    ✅     |    ✅    |
| Brave |    ✅    |   ✅   |    ✅    |    ✅    |
| Opera |    ✅    |    ✅    |    ✅    |    ✅    |
| OperaGX |    ✅    |    ✅    |    ✅    |    ✅    |
| Vivaldi |    ✅    |    ✅    |    ✅    |    ✅    |
| Yandex |    ✅    |    ✅    |    ✅    |    ✅    |
| CocCoc |    ✅    |    ✅    |    ✅    |    ✅    |
| Firefox |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Dev |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox ESR |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Nightly |    ✅    |   ✅   |    ✅    |    ✅    |
| Safari   |    ❌     |   ❌    |    ❌     |    ❌|

### Linux

| 浏览器    | 密码 | Cookie | 书签 | 历史记录 |
| :----- | :------: | :----: | :------: | :-----: |
| Google Chrome |    ✅     |   ✅    |    ✅     |    ✅    |
| Google Chrome Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Chromium |    ✅    |    ✅    |    ✅    |    ✅    |
| Microsoft Edge |    ✅    |   ✅   |    ✅    |    ✅    |
| Brave |    ✅    |   ✅   |    ✅    |    ✅    |
| Opera |    ✅    |    ✅    |    ✅    |    ✅    |
| Vivaldi |    ✅    |    ✅    |    ✅    |    ✅    |
| Chromium |    ✅     |   ✅    |    ✅     |    ✅    |
| Firefox |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Beta |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Dev |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox ESR |    ✅    |   ✅   |    ✅    |    ✅    |
| Firefox Nightly |    ✅    |   ✅   |    ✅    |    ✅    |

## 安装运行
### 安装

可下载已编译好，可直接运行的 [二进制文件](https://github.com/moonD4rk/HackBrowserData/releases)

> 某些情况下，这款安全工具会被 Windows Defender 或其他杀毒软件当作病毒导致无法执行。代码已经全部开源，可自行编译。

### 从源码编译

仅支持 `go 1.18+` 以后版本，一些函数使用到了泛型

``` bash
$ git clone https://github.com/moonD4rk/HackBrowserData

$ cd HackBrowserData/cmd/hack-browser-data

$ CGO_ENABLED=1 go build
```

### 跨平台编译

由于用到了 `go-sqlite3` 库，在跨平台编译时需提前安装支持目标平台的 `GCC` 工具，下面以 `MacOS` 下分别编译 `Windows` 和 `Linux` 程序为例：

#### Windows

``` shell
brew install mingw-w64

CGO_ENABLED=1 GOOS=windows GOARCH=amd64 CC=x86_64-w64-mingw32-gcc go build
```

#### Linux

``` shell
brew install FiloSottile/musl-cross/musl-cross

CC=x86_64-linux-musl-gcc CXX=x86_64-linux-musl-g++ GOARCH=amd64 GOOS=linux CGO_ENABLED=1 go build -ldflags "-linkmode external -extldflags -static"
```

### 运行
双击直接运行，也可以使用命令行调用相应的命令。

```
PS C:\test> .\hack-browser-data.exe -h
NAME:
   hack-browser-data - Export passwords/cookies/history/bookmarks from browser

USAGE:
   [hack-browser-data -b chrome -f json -dir results -cc]
   Export all browingdata(password/cookie/history/bookmark) from browser
   Github Link: https://github.com/moonD4rk/HackBrowserData

VERSION:
   0.4.2

GLOBAL OPTIONS:
   --verbose, --vv                   verbose (default: false)
   --compress, --zip                 compress result to zip (default: false)
   --browser value, -b value         available browsers: all|chrome|opera-gx|vivaldi|coccoc|brave|edge|chromium|chrome-beta|opera|yandex|firefox (default: "all")
   --results-dir value, --dir value  export dir (default: "results")
   --format value, -f value          file name csv|json (default: "csv")
   --profile-path value, -p value    custom profile dir path, get with chrome://version
   --help, -h                        show help (default: false)
   --version, -v                     print the version (default: false)


PS C:\test>  .\hack-browser-data.exe -b all -f json --dir results -zip
[NOTICE] [browser.go:46,pickChromium] find browser Chrome success  
[NOTICE] [browser.go:46,pickChromium] find browser Microsoft Edge success  
[NOTICE] [browsingdata.go:59,Output] output to file results/microsoft_edge_download.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/microsoft_edge_password.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/microsoft_edge_creditcard.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/microsoft_edge_bookmark.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/microsoft_edge_cookie.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/microsoft_edge_history.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/chrome_history.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/chrome_download.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/chrome_password.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/chrome_creditcard.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/chrome_bookmark.json success  
[NOTICE] [browsingdata.go:59,Output] output to file results/chrome_cookie.json success  

```

### 基于此工具的一些其他项目
[Sharp-HackBrowserData](https://github.com/S3cur3Th1sSh1t/Sharp-HackBrowserData)

[Reflective-HackBrowserData](https://github.com/idiotc4t/Reflective-HackBrowserData)


<!--auto_detail_active_begin_e1c6fb434b6f0baf6912c7a1934f772b-->
## 项目相关


## 最近更新

#### [v0.4.2] - 2022-05-01

**更新**  
- 新增导出扩展
- 新增设置控制台 log 日志的色彩  
- 文档添加 HackBrowserData 的 logo

#### [v0.4.1] - 2022-04-20

**更新**  
- 支持所有浏览器导出 local storage
- 修复 firefox ans1 数据结构  
- 修复 windows 平台上 chromium 密钥查找失败的问题

#### [v0.4.0] - 2022-04-18

**更新**  
- 支持 Go 1.18 泛型，重构项目布局  
- 添加对所有已发布的 Firefox 的支持  
- 为命令行日志添加颜色输出  
- 某些 Linux 发行版的 chromium 现可不使用 D-Bus 获取主密钥  
- 修复 Chromium cookie 文件路径错误  
- Windows 下解密 Chromium 密码时增加 AES 块大小检查  
- 修复 Windows 导出信用卡失败

#### [v0.3.7] - 2021-12-13

**新功能**  
- 为macOS和Windows添加Yandex浏览器  
- 为macOS和Windows添加CocCoc浏览器  

**修复**  
- 优化中文版README内容  
- 为AES解密添加密文长度检查  
- 更新依赖组件github.com/tidwall/gjson至1.9.3  
- 升级go-sqlite3版本，移除编译警告

<!--auto_detail_active_end_f9cf7911015e9913b7e691a7a5878527-->
