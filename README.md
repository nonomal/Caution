# biliup-app
![GitHub all releases](https://img.shields.io/github/downloads/forgqi/Caution/total)
[![Telegram](https://img.shields.io/badge/Telegram-Group-blue.svg?logo=telegram)](https://t.me/+IkpIABHqy6U0ZTQ5)

bilibili投稿客户端，支持Windows，Linux，macOS。

文档地址：<https://forgqi.github.io/biliup-app>

主要是为了解决现有网页端不能多p投稿的问题，虽然现有b站客户端可以多p
但是有几个问题：
* 仅支持Windows，不支持Linux，macOS
* 不能批量选择文件，多p只能多次单选文件
* 投稿线路对国外不友好，速度较慢稳定性较差，且不能自行切换
* 不能调整单视频上传并发数，单视频限制大小4G以内
* 仅能通过短信登录

[下载地址](https://github.com/ForgQi/Caution/releases)

若 Windows 7 安装出错请先安装 [WebView2](https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/#download-section)
后再重新安装
### SEE ALSO

* 自动录播投稿[工具](https://github.com/ForgQi/biliup)
* 命令行投稿工具[CLI](https://github.com/ForgQi/biliup-rs)
---
![login](.github/resource/login.png)
![main](.github/resource/main.png)

基于TAURI: ` GUI: Svelte , 后端: Rust`
## Roadmap
- [x] 短信登录, 二维码登录
- [ ] 上传视频封面
- [x] 自由切换投稿线路
- [x] 设置投稿并发数
- [ ] 多p按照文件名排序
- [ ] 远程部署agent，本地操作
- [ ] 插件系统，如自动录播后上传
