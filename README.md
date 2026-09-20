# 安哥拉葡语·第1周 v3

这是可通过 Netlify 等 HTTPS 静态网站托管的离线 PWA 课程。

## v3 修正
- 首屏课程数据直接内置在 index.html，不依赖首次 fetch content.json。
- Service Worker 使用正确的 audio/ 路径，并预缓存全部 63 个 MP3。
- 修复旧版 v2 的 Service Worker 缓存路径错误。
- 课程首页会自动指向下一个未完成日。
- 每天有独立小测试。
- 学习进度使用 `angolaWeek1ProgressV3` 保存。
- 支持 iPhone Safari “添加到主屏幕”。

## Netlify 更新
登录 Netlify，进入现有网站的 Deploys 页面，把本文件夹整体拖到手动部署区域即可更新现有网站。

## 音频说明
本版本 MP3 是葡萄牙语基准 TTS，用于离线播放工程验证，不是安哥拉母语者录音。正式版应替换为获得授权的安哥拉母语者录音/经审核的 pt-AO 音频。
