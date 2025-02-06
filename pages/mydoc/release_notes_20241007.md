---
title: "2024/10/07版リリース"
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: Oct  07, 2024
summary: "Version 5.0 of the Documentation theme for Jekyll changes some fundamental ways the theme works to provide product-specific sidebars, intended to accommodate a site where multiple products are grouped together on the same site rather than generated out as separate outputs."
sidebar: mydoc_sidebar
permalink: release_notes_20241007.html
folder: mydoc
---
##### 語学講座CS2の2024/10/07版をリリースしました。今回の更新の適用は必須ではありません。
#####                
##### [語学講座CS2](https://csreviser.github.io/CaptureStream2/)
#####  
#####  ffmpegパス指定機能追加

### ＜変更内容＞　　　
### ＜全OS共通＞
##### （１）ffmpegパス指定機能追加
##### ※ffmpegパスを指定しない場合は、初期値は従来と同じ動作となります。
##### ※ffmpegパスを指定した場合は、指定したパスのffmpegが使われます。
##### ※指定したパス（フォルダ）にffmpegが存在しなくても設定はできますが、実行時にエラーとなります。
##### 
##### ※今回の更新は適用必須ではありません。
##### ※MacOS版は動作確認していません。今回から「macos-12」環境でのビルドを廃止し「macos-14」に移行しています。
#####  　　　  
#####  　　　  
#####  　　　  
#####  　
* ### Windows用
**[CaptureStream2-Windows-x86-20241007.zip 【32bit版】](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-Windows-x86-20241007.zip)**
**[CaptureStream2-Windows-x64-20241007.zip 【64bit版】](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-Windows-x64-20241007.zip)**　　　　　　　　　　　　　　　　　　

* ### Ubuntu用（参考公開）     
**[CaptureStream2-Ubuntu22.04-20241007.zip](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-Ubuntu-20241007.zip)**
**[CaptureStream2-Ubuntu24.04-20241007.zip](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-Ubuntu2404-20241007.zip)**
#####  　　　  
#####  
#####  　　　  
#####  

* **Mac版は[【MacOSユーザの方へ】](https://csreviser.github.io/CaptureStream2/macos)および[【必要要件】](https://csreviser.github.io/CaptureStream2/requirements)をご確認の上、動作確認にご協力いただける方のみ下記リンクから実行ファイルをダウンロードしてください。**  
* ### MacOS用 （参考公開）  
### [CaptureStream2-MacOS-20241007.dmg](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-MacOS-20241007.dmg)
### [macOS10.13以降　Intel向バイナリ](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-MacOS-qt5-Intel-20241007.dmg)
### [ffmpegなし　Universalバイナリ](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-MacOS-non-ffmpeg-20241007.dmg)
#### ※ffmpegは使用環境に合わせて準備してください。[ffmpeg最新版入手サイト](https://csreviser.github.io/CaptureStream2/FFMPEG)
####  　　　  
####  　　　  
* ### MacOS (ffmpeg Apple Silicon Binary）テスト用
### [CaptureStream2-MacOS-arm-20241007.dmg](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-MacOS-arm-20241007.dmg)　　
#### 「"CaptureStream2.app"は壊れているため開けません。」と表示される場合は[こちら](https://www.google.com/search?client=ubuntu-sn&channel=fs&q=%E3%81%AF%E5%A3%8A%E3%82%8C%E3%81%A6%E3%81%84%E3%82%8B%E3%81%9F%E3%82%81%E9%96%8B%E3%81%91%E3%81%BE%E3%81%9B%E3%82%93)を参考にお試しください。
####  　　　  
* ### MacOS-15 (Beta）テスト用  
### [macOS11以降　Universalバイナリ（macOS15使用）](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-MacOS15-20241007.dmg)
### [macOS10.13以降　Intel向バイナリ（macOS15使用）](https://github.com/CSReviser/CaptureStream2/releases/download/20241007/CaptureStream2-MacOS15-qt5-Intel-20241007.dmg)
####  　　　  
  * **Macユーザー間の情報交換の場として[こちらに【macOS関係の情報交換】](https://github.com/CSReviser/CaptureStream2/discussions/24)を作成しました。**
####  　　
####  　　　  
####  　　　  
####  　　　 
{% include links.html %}
