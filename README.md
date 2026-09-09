# 二维码文件单向传输工具

## 页面说明

- `index.html`：接收端。手机浏览器打开，用摄像头扫描发送端屏幕上的动态二维码，还原文件或文字。
- `sender.html`：发送端。离线 Windows 电脑用 Edge/Chrome 打开，选择文件/文件夹或输入文字，循环播放动态二维码。

## 托管到 GitHub Pages 后

- 接收端地址：`https://<你的用户名>.github.io/<仓库名>/`
- 发送端地址：`https://<你的用户名>.github.io/<仓库名>/sender.html`

## 使用注意

- 接收端调用摄像头必须在 HTTPS 下打开（GitHub Pages 本身就是 HTTPS）。
- 发送端不需要联网，可下载 `sender.html` 到离线电脑后双击打开。
- 发送端文件上限 20MB；文字模式上限 1MB。
