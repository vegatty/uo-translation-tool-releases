# UO翻訳ツール

UOの英語クエストや文書を日本語で読むための、Windows用ツールです。
画面の英文を撮影して文字にし、Chromeで開いたChatGPTへ送って翻訳します。

## ダウンロード

**[v0.12.0 β1 — Windows用ZIP](https://github.com/vegatty/uo-translation-tool-releases/releases/download/v0.12.0-beta1/UoTranslation-v0.12.0-beta1-win-x64.zip)**（約56MB）

[リリース説明](https://github.com/vegatty/uo-translation-tool-releases/releases/tag/v0.12.0-beta1) / [SHA-256](https://github.com/vegatty/uo-translation-tool-releases/releases/download/v0.12.0-beta1/UoTranslation-v0.12.0-beta1-win-x64.zip.sha256)

ZIPを「すべて展開」し、フォルダー内の **UoTranslation.App.exe** を起動してください。GitHubの「Source code」はアプリ本体ではありません。フォルダー全体を残して使用します。

## 必要な環境

- Windows 11（64bit）、Windowsの英語OCR
- Google Chrome、ChatGPTアカウント、インターネット接続

APIキーや有料AI契約は不要です。AIサービス側の利用制限はあります。
Chromeを既定ブラウザーにする必要はありません。.NETとAutoHotkeyは同梱しています。

## 使い方

1. Chromeで翻訳専用の空のChatGPTチャットを開き、アプリのセットアップを行います。
2. UOの英文に撮影枠を合わせ、「撮影」を押します。
3. 長文は自分でスクロールし、少し重ねて続きを撮影します。
4. 「OCR・履歴」で画像と英文を確認し、誤読があれば修正します。
5. 「翻訳」を押し、Chromeに返った日本語訳を確認します。

1枚だけでも翻訳できます。撮影だけでは送信しません。翻訳後も現在の画像と英文は残り、撮影を追加できます。別のクエストへ移るときは「新しく始める」を使います。

## 確認範囲と制限

- 同一処理の開発候補で、CCの複数枚撮影→Chromeへの送信→新しい日本語訳、消去確認のキャンセル後保持を実機確認しました。名称・文書を整理した配布ビルド自体の実機動作は未確認です。
- EC、別PC、高DPI、長時間使用は未検証です。
- 読み順・人物名などのOCR誤読、AIの誤訳や省略が起こります。数字・条件・名前・行き先は原画像と比べてください。
- 設定の開閉やサイズ変更には、性能測定で遅くなった項目が残っています。
- ジャーナル専用機能、日本語返信、撮影と同時のAI送信は含みません。
- 画像と本文は自動保存しません。消去・終了後の復元はできません。
- 未署名アプリです。セキュリティ保護を無効化して使用しないでください。

ゲーム内の操作・発言の自動化、ゲームのメモリ・通信・ファイルの変更は行いません。撮影画像や履歴を自動収集しません。初期準備や「翻訳」を実行すると、その指示または翻訳用文章を利用者のChatGPTへ送ります。

## 試用案内・不具合報告

無料で試用できます。開発途中のため動作保証はありません。原画像と翻訳内容、各サービスの利用条件を確認して使用してください。

不具合報告は任意です。[Issues](https://github.com/vegatty/uo-translation-tool-releases/issues)へ、版名、CC/EC、操作手順、エラー表示を分かる範囲でお知らせください。認証情報・アカウント名は不要です。

本体の試用案内はZIP内のTRIAL-NOTICE.txt、第三者ソフトウェアの通知はlicenses、AutoHotkeyの対応ソースはthird-party-sourceに含みます。第三者のライセンス上の権利を制限しません。本体へ新たなオープンソースライセンスを付与するものではありません。

UO・Google Chrome・ChatGPT/OpenAIの公式製品ではありません。公式シャードでの利用許可を確認済みと示すものではありません。

Copyright (c) 2026 Rina@227

