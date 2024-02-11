# XR Interaction Toolkit WebView Example

This Unity project demonstrates how to use [Vuplex 3D WebView](https://developer.vuplex.com) with Unity's [XR Interaction Toolkit (XRI)](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@1.0/manual/index.html). It includes XRI and its dependencies, so all you need to do is [import 3D WebView](https://store.vuplex.com/webview/overview) into the project. For more information on 3D WebView's support for XRI, please see [this article](https://support.vuplex.com/articles/xr-interaction-toolkit).

<p align="center">
  <img alt="demo" src="./demo.gif" width="640">
</p>

## Steps taken to create this project

1. Created a new project with Unity 2020.3.24.
2. Installed the following packages through the Package Manager:
- XR Interaction Toolkit (v2.1.1)
- XR Management
- Oculus XR Plugin
3. Installed 3D WebView (omitted via [.gitignore](./.gitignore))
4. Created the XritWebViewDemo scene, which demonstrates how to use a [CanvasWebViewPrefab](https://developer.vuplex.com/webview/CanvasWebViewPrefab) and [CanvasKeyboard](https://developer.vuplex.com/webview/CanvasKeyboard).
