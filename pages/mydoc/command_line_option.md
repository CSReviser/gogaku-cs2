---
title: コマンドラインオプション
keywords: "features, capabilities, scalability, multichannel output, dita, hats, comparison, benefits"
last_updated: "Feb 3, 2025"
#summary: ""
published: true
sidebar: mydoc_sidebar
permalink: command_line_option.html
folder: mydoc
---

## コマンドラインオプション    

#### 語学講座CS2 は、GUI（グラフィカル・ユーザ・インターフェイス）のアプリケーションですが、GUIを使わないコマンドラインで使うオプションがあります。このオプションは、スケジュール実行させるときに利用できます。
#### 　　　　
#### ＜コマンド形式＞
#### path\CaptureStream2 -nogui <番組ID>  <その他オプション>
#### 　　　　
#### path\  ：　CaptureStream2 本体があるフォルダのパス
#### CaptureStream2  ：　Windowsの場合は拡張子「.exe」が必要
#### -nogui　：　GUIを立ち上げずに実行するためのオプション
#### <番組ID>　：　xxxx_xx　形式の番組ID、半角スペースで区切って複数指定可能
#### 番組IDを指定しない場合は、GUIで設定した番組を録音します。
#### 番組IDを指定た場合は、GUIで設定した番組は録音されず、コマンドラインで指定した番組IDのみ録音します。
#### 配信がない番組ID、正しくない番組IDを指定た場合は、エラーとはならず無視されます。GUIで設定した番組も録音されません。
#### <-t "タイトルタグ形式指定">　：　カスタマイズメニューの「タイトルタグ設定」相当の設定ができます。
#### <-f "ファイル名形式指定">　：　カスタマイズメニューの「ファイル名設定」相当の設定ができます。
#### <-o "保存フォルダのフルパス指定">　：　カスタマイズメニューの「保存フォルダ設定」相当の設定ができます。
#### <-e "拡張子を指定">　：　メインウィンドウの「拡張子」相当の設定ができます。
#### <-z>　：　[前週]にチェックを入れた時に相当する動作をします。
#### <-b>　：　[前週]にチェックを入れた時とチェックしなかった時にに相当する動作を双方実行します。
#### <-s>　：　[応用編分離]にチェックを入れた時に相当する動作をします。該当する欧州系語学講座との組み合わせでのみ機能します。
#### 　　　　
#### ※全てのコマンドラインオプションを使用できるのは、2024/08/16版以降です。
#### ※省略して指定しない<オプション>はGUIで設定した内容となります。GUIで設定していない場合はデフォルト値となります。


*** 
 <link rel="shortcut icon" type="image/x-icon" href="https://avatars.githubusercontent.com/u/46049273?v=4">
 <meta name="twitter:image:src" content="https://avatars.githubusercontent.com/u/46049273?v=4">
