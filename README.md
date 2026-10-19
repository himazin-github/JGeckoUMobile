# JGecko U for Android

**JGecko U for Android** is an Android port of [JGecko U](https://github.com/BullyWiiPlaza/JGeckoU),
the Wii U RAM debugger / cheat code manager.
Developer: **ドリアン (Dorian)**

Wii U向けTCPGeckoデバッガ **JGecko U** のAndroid移植版です。
開発者: **ドリアン**

## ダウンロード

[Releases](../../releases) ページから最新の `JGeckoU-Android-debug.apk` をダウンロードしてください。

> デバッグ署名のAPKのため、インストール時に「提供元不明のアプリ」の許可や
> Play Protectの警告が表示されることがあります。

## 機能

| タブ | 機能 |
|------|------|
| 検索 | メモリ検索 (8/16/32/64bit、10進/0x16進、絞り込み検索、結果タップで書き換え) |
| メモリ | ヘックスダンプ表示と任意アドレスへの読み書き (ポーク) |
| コード | GCTUチートコードの適用。JGecko U形式のXMLコードリストに対応し、**スプラトゥン (AGMJ01) のコード集を内蔵**。チェックで選択して一括適用。XMLファイルの追加読み込みにも対応 |
| 逆アセ | 内蔵PowerPCディスアセンブラ |
| その他 | 本体の一時停止/再開、カーネルモード切替 |

## 動作要件

- **Wii U**: [TCP Gecko Installer](https://github.com/BullyWiiPlaza/tcpgecko) のサーバーが起動していること
- **Android**: Android 8.0 以上
- Wii UとAndroid端末が同一LANに接続していること (TCP **7331**番ポート)

## 使い方

1. Wii UでTCP Geckoサーバーを起動し、ゲームを開始する
2. アプリにWii UのIPアドレスを入力して「接続」
3. 「コード」タブで使いたいコードにチェックを入れ「選択を送信」

## クレジット

- [JGecko U](https://github.com/BullyWiiPlaza/JGeckoU) / [TCP Gecko Installer](https://github.com/BullyWiiPlaza/tcpgecko) — Bully@Wiiplaza (BullyWiiPlaza)
- Android移植 — **ドリアン (Dorian)**
