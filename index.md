---
title: "Privacy Policy — Meet Light for SwitchBot"
---

# プライバシーポリシー — Meet Light for SwitchBot

最終更新日: 2026年11月24日

「Meet Light for SwitchBot」（以下「本拡張機能」）は、利用者のプライバシーを最優先に設計されています。本拡張機能は開発者側のサーバーを一切持たず、利用者のデータを収集・送信・販売しません。

## 1. 保存する情報

本拡張機能が保存する情報は以下のとおりで、**すべて利用者のブラウザのストレージ内にのみ保存されます**。開発者を含む第三者がアクセスすることはありません。

**端末ローカル（`chrome.storage.local` / `chrome.storage.session`）に保存されるもの:**

- SwitchBot APIのトークンおよびシークレット（利用者が設定画面で入力したもの）
- 追加したライト（電球・テープライト等）のデバイスIDと名前
- 明るさの設定値
- 会議中かどうかのフラグ（ブラウザ終了時に消去されるセッション領域）

**Chrome同期領域（`chrome.storage.sync`）に保存されるもの:**

- Gumroadライセンスキーと最終検証日時
- 本拡張機能のインストール日時（無料トライアルの残日数計算のため）

Chrome同期領域のデータは、利用者がChromeにGoogleアカウントでログインし同期を有効にしている場合、Googleの同期サーバーを経由して同じアカウントの他の端末と共有されます（この同期はChromeブラウザ自体の標準機能であり、開発者はアクセスできません）。同期を無効にしている場合は端末ローカルにのみ保存されます。

## 2. 外部との通信

本拡張機能が通信する先は以下の2つのみです。

| 通信先 | 目的 | 送信される内容 |
|---|---|---|
| SwitchBot API（api.switch-bot.com） | ライトの操作・デバイス一覧の取得 | 利用者自身のSwitchBotトークンによる認証情報と、点灯色・明るさ等の操作コマンド |
| Gumroad License API（api.gumroad.com） | ライセンスキーの有効性確認 | 商品IDとライセンスキーのみ |

上記以外のサーバーへの通信は一切行いません。アクセス解析・広告・トラッキングの類も含まれていません。

## 3. タブURLの取り扱い

本拡張機能は、会議への参加・退出を検知するために Google Meet（meet.google.com）のタブURLがあるかどうかを**ブラウザ内で**確認します。

- 確認の対象は `meet.google.com` のタブのみです。
- URL・閲覧履歴・会議の内容・参加者情報などが外部へ送信されることは一切ありません。
- 会議の音声・映像・チャットには一切アクセスしません。

## 4. 第三者提供

利用者の情報を第三者に提供・販売・共有することはありません。

## 5. 本ポリシーの変更

本ポリシーを変更する場合は、本ページを更新し、重要な変更については拡張機能の更新情報でお知らせします。

## 6. お問い合わせ

本ポリシーに関するご質問は、以下までご連絡ください。

- 連絡先: sho.amano@r-and-s.com

---

※ 本拡張機能は SwitchBot（Woan Technology）および Google の公式製品ではなく、両社とは提携関係にありません。

---

# Privacy Policy — Meet Light for SwitchBot (English)

Last updated: November 24, 2026

"Meet Light for SwitchBot" (the "Extension") is designed with your privacy as the top priority. The Extension operates without any developer-side server and does not collect, transmit, or sell any user data.

## 1. Data stored

All data listed below is stored **only in your browser's storage**. No third party, including the developer, can access it.

**Stored locally on your device (`chrome.storage.local` / `chrome.storage.session`):**

- Your SwitchBot API token and secret (entered by you on the settings page)
- The device IDs and names of the lights (bulbs, strip lights, etc.) you added
- Brightness setting
- An in-meeting flag (kept in session storage, cleared when the browser closes)

**Stored in Chrome sync storage (`chrome.storage.sync`):**

- Your Gumroad license key and its last verification time
- The installation date of the Extension (used to calculate remaining free-trial days)

If you are signed in to Chrome with a Google account and have sync enabled, Chrome sync data is shared with your other devices through Google's sync servers (this is a standard feature of the Chrome browser itself; the developer has no access to it). If sync is disabled, the data stays on your device.

## 2. Network communication

The Extension communicates with only the following two endpoints:

| Endpoint | Purpose | Data sent |
|---|---|---|
| SwitchBot API (api.switch-bot.com) | Controlling your lights and listing devices | Authentication using your own SwitchBot token, and commands such as color and brightness |
| Gumroad License API (api.gumroad.com) | Verifying your license key | The product ID and your license key only |

No other servers are contacted. The Extension contains no analytics, advertising, or tracking of any kind.

## 3. Handling of tab URLs

To detect when you join or leave a meeting, the Extension checks **within your browser** whether a Google Meet (meet.google.com) tab is open.

- Only meet.google.com tabs are checked.
- URLs, browsing history, meeting contents, and participant information are never sent anywhere.
- The Extension never accesses meeting audio, video, or chat.

## 4. Third-party disclosure

We do not provide, sell, or share your information with any third party.

## 5. Changes to this policy

If this policy changes, this page will be updated, and significant changes will be announced in the Extension's release notes.

## 6. Contact

For questions about this policy, please contact:

- sho.amano@r-and-s.com

---

Note: This Extension is not an official product of SwitchBot (Woan Technology) or Google and is not affiliated with either company. "SwitchBot" and "Google Meet" are trademarks of their respective owners.
