# vscode_for_android

这是一个使用 code-server 实现的 VS Code 安卓版。这个方案也有些人实现了，这里也是提供其中一种。

体积会比较大，由于所需要的资源都是整个运行初始化需要的，所以将资源集成到服务器，再动态下载的意义不大。

所以大家综合权衡这种方案与其他开发者的方案。

原理是运行 code-server 再使用 webview 加载视图，会有一些bug，但已经能有一些可观的表现。

这个项目是开源的，上层框架是 Flutter，VS Code不是运行在 Flutter 中的，只有初始化的那个界面是。

工作比较忙，可能处理问题较慢，见谅。

Cheers! 🍻



## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
