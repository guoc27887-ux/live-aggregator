# 聚合直播（壳 App）

一个最小的 iOS 壳应用：打开即用 WKWebView 加载直播聚合站
https://live.wxhbts.com ，站内直播、弹幕、换台都走网页本身。

- 部署目标 iOS 15.0，iPhone / iPad 通用
- Bundle ID：com.liveaggregator.app
- 桌面显示名：聚合直播
- 未签名打包：GitHub Actions 工作流 `.github/workflows/build-unsigned-ipa.yml`
  会打出未签名 IPA，下载后需用自己的 Apple ID 通过 SideStore / AltStore
  等工具签名侧载安装（免费签名有效期 7 天）。
