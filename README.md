# Online m3u8 Player

一个基于 Web 的在线 m3u8 视频播放器，可以部署到 GitHub Pages。

## 功能特点

- 支持播放 m3u8 格式的视频流
- 响应式设计，适配不同屏幕尺寸
- 兼容主流浏览器（Chrome, Firefox, Safari, Edge）
- 简单易用的界面

## 使用方法

1. 在输入框中输入有效的 m3u8 视频链接
2. 点击"加载视频"按钮开始播放
3. 使用视频控件进行播放、暂停、调节音量等操作

## 部署到 GitHub Pages

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中找到 "Pages" 选项
3. 选择部署源为 "GitHub Actions" 或直接选择分支
4. 保存设置后等待部署完成

## 本地运行
```bash
npm install
npm start
```
然后在浏览器中打开 http://localhost:8080

## 注意事项

- 视频链接必须是公开可访问的
- 某些视频可能有跨域限制，需要相应的 CORS 设置
- 本播放器仅支持 http/https 协议的 m3u8 链接，不支持本地文件

## 使用的开源技术

- [hls.js](https://github.com/video-dev/hls.js/) - 用于在支持 MSE 的浏览器中播放 HLS
