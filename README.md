# mecab_dart_sample

[mecab_dart](https://github.com/dttvn0010/mecab_dart)を使ってみました。

使い方は大変簡単で、このコミット分だけで使えました。
https://github.com/ken1flan/mecab_dart_sample/commit/3e38a4445a5c818445ff9a680fd69180a3e18fac

実際に動かしてデバッガで見てみると、↓のようになっていて…。
テキストがトークンに分割されて、トークンの属性もfeaturesに保存されていました。
![image](https://user-images.githubusercontent.com/2942348/179429311-0e07bc0e-1703-4b8a-ab18-86a44ad20941.png)

MeCabとIPA辞書は．GPL、LGPL、またはBSDライセンスに従って…とあるので、商用利用も大丈夫そう。
https://taku910.github.io/mecab/
![image](https://user-images.githubusercontent.com/2942348/179429885-dfa2f9dd-aef8-46d0-8699-7f68598e9839.png)

**注意点**
- [mecab_dart](https://github.com/dttvn0010/mecab_dart)はflutterのプラグインです。

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
