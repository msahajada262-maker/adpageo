# Ad Page

A simple ad-hosting HTML page created using GitHub Pages.

This page can be used to load advertisements inside Flutter WebView or other apps.

## 🔗 Live Demo

[Visit Live Ad Page](https://msahajada262-maker.github.io/adpageo)

## 📂 Files

- `index.html` – Main ad HTML page with embedded iframe

## 📱 Use in Flutter WebView

```dart
WebViewWidget(
  controller: WebViewController()
    ..setJavaScriptMode(JavaScriptMode.unrestricted)
    ..loadRequest(Uri.parse('https://msahajada262-maker.github.io/adpage')),
)
