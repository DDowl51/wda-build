# wda-build

只放一个 GitHub Actions workflow，用 macos-13 + Xcode 14.3.1 云编译
appium/WebDriverAgent (tag v5.15.5)，产出未签名的 WebDriverAgent.ipa。
公开仓库 → macOS runner 免费、不排队。无任何密钥/业务代码。

用法：Actions 页 → '编译 WDA' → Run workflow → 跑完在 Artifacts 下载 WebDriverAgent-ipa。

