# flutter_application_sample
https://zenn.dev/hagakun_dev/articles/23bba803cbec13 をベースに作成

## セットアップ
- VS Codeをインストール
- Flutterプラグインをインストール
- Dartプラグインをインストール
- コマンドパレットを開くには、Control+ Shift+を押しますP。
- コマンドパレットに `flutter` と入力します 
  - SDKのインストールを求められるので、保存場所を指定してDownsloadする
  - 環境変数PATHの設定を聞かれるのでインストールしたパスを設定
  - `flutter --version` で返ってくればOK
  - `Flutter: New Application Project`を選択
  - プロジェクトの保存先を指定し、プロジェクト名を入力する
- VS Codeの `Run`⇒`Start Debugging`を選択
- アプリが起動する（どのブラウザで起動するかを聞かれる）


## Android機でのデバッグ準備
https://qiita.com/yiwa81/items/960e581f6a9e65802090

- 設定 > システム > 端末情報 を選択
- ビルド番号を7回タップする。これで、開発者向けオプションが有効となる
- 設定 > システム > 開発者向けオプション を選択
- USBデバッグ を有効にする

デバッグ
- PCとスマホを接続
- ファイル転送モードに変更
  - スマホ側でも許可する
- VSCode の右下で スマホを選択する（デフォルトだとブラウザになっている）
- VSCode で Run > Debug


A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
