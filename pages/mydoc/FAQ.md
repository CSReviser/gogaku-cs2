---
title: FAQ（よくある質問）
keywords: "features, capabilities, scalability, multichannel output, dita, hats, comparison, benefits"
last_updated: "Feb 4, 2025"
#summary: ""
published: true
sidebar: mydoc_sidebar
permalink: FAQ.html
folder: mydoc
---

**[トラブルシューティング](./troubleshooting)および[TOPページ](./index)の[＜既知課題＞](./#%E6%97%A2%E7%9F%A5%E8%AA%B2%E9%A1%8C-1)もご確認ください。**

*** 
### **＜全OS共通＞**

*** 

* **Q:　英語以外の語学講座には対応していないのですか？**
* **A:　対応しております。任意らじる聴き逃し番組ボタンに録音したい語学講座を設定することにより英語以外の語学講座も録音できます。設定手順は[任意らじる聴き逃し番組設定](./SETTING_COURSES)を、対象講座は[対象講座と番組ID一覧](./courses_name)をご確認ください。**

*** 

* **Q:　先週放送分を録音できると思っていたのですが、今週放送分が録音されました。以前は放送の１週間遅れだったと思うのですが変わったのでしょうか？**
* **A:　現在は初回放送後１週間、録音できるようになっています。メインウィンドウ下部の［前週］チェックボックスにチェックを入れると以前と同様に放送翌週月曜日10時から1週間分の録音ができます。設定手順は[［前週］チェックボックス](./last_week)を、対象講座は[対象講座と番組ID一覧](./courses_name)をご確認ください。**

*** 

* **Q:　拡張子は何を選択すれば良いですか？**
* **A:　初期値は「m4a」になっています。「m4a」は現在一般的に使用されている主要なOS環境（Windows、macOS、Linux、Android、iOS等）で再生可能です。mp3専用プレーヤを使う場合は「mp3」を選択してください。詳細は[拡張子の選択](./SETTING_extension)を参考にしてください。**

*** 

* **Q:　録音される音声ファイルのサイズを小さくできませんか？**
* **A:　拡張子の選択で数値「xxk」が小さい「mp3-xxk-M」を選ぶと、数値が小さいほどファイルサイズを小さくできます。ただし、数値が小さくなるほど音質も低下する点に注意してください。一方、「m4a」形式ではファイルサイズを小さくすることはできません。ストリーミングに使用されるコーデックは「aac」であり、「m4a」に変換する際もコーデック自体は「aac」のままです。変換によって変更されるのはコンテナ（入れ物）の形式のみで、元の「aac」のデータが保持されるため、ファイルサイズは元のデータ量に依存します。
詳細は[拡張子の選択](./SETTING_extension)を参考にしてください。**

*** 

* **Q:　曜日や時間を指定して自動実行できますか？**
* **A:　語学講座CS2には曜日や時間を指定して自動実行する機能はありませんが、OSの機能(タスクスケジューラ)などと組み合わせて自動実行させることができます。引数に「-nogui」を指定してください。ubuntu(Linux)では環境変数『DISPLAY=:0』の指定も必要です。**


*** 
### **＜Windows＞**
*** 

* **Q:　Windows版で「WindowsによってPCが保護されました」と警告が表示されます。**
* **A:　Windowsでは初回実行時に「WindowsによってPCが保護されました」と警告が表示されますが「詳細情報」をクリックして表示される「実行」をクリックしてください。[Windows版インストール手順](./install_win)を参考にしてください。**

*** 

* **Q:　32bit版はありますか？**
* **A:　あります。最新版のリリースノート（ブログ）をご確認ください。32bit版は配布しているzipのファイル名に「x86」という文字が含まれます。64bit版はファイル名に「x64」という文字が含まれます。**

*** 

* **Q:　Windows8.1（Windows7）で使用できますか？**
* **A:　Qt5版で使用可能ですが、Windows8.1以前はMicrosoftのサポートが終了しているので使用はおすすめできません。また語学講座CS2の必要要件は2024年度現在Qt6.5以降なので、通常の実行ファイルはWindows8.1以前には非対応です。[QtバージョンとWindows対応](./Qt_vs_OS#windows)を参照ください。Qt5版は配布しているzipのファイル名に「qt5」という文字が含まれます。自己責任でご使用ください。「ffmpeg.exe」は使用環境で動作するものを準備してください。**

*** 
### **＜ubuntu＞**
*** 

* **Q:　配布されている実行ファイルが動作しません。**
* **A:　[Ubuntu版インストール(ビルド)手順](./install_linux)を参考に実行する環境でビルドしてください。**

*** 

* **Q:　ubuntu以外のLinux系OS（ディストリビューション）で使えませんか？**
* **A:　使用可能です。配布しているubuntu版実行ファイルが動作しない場合は、[Ubuntu版インストール(ビルド)手順](./install_linux)を参考に実行する環境でビルドしてください。**

*** 

* **Q:　32bit版はありますか？**
* **A:　配布している実行ファイルはありませんが、[Ubuntu版インストール(ビルド)手順](./install_linux)を参考に実行する環境でビルドしてください。**

*** 
### **＜macOS＞**
*** 

* **Q:　macOSで使えませんか？macOS版はありませんか？**
* **A:　語学講座CS2はmacOSでも使用可能です。複数のMacユーザから動作報告を頂いています。**

*** 

* **Q:　macOSは「サポート対象外」とは、どのような意味ですか？**
* **A:　動作確認を行うMac実機環境がなく、またMacに関する知識が乏しいので「サポート対象外」としています。問題解決に向けて情報提供いただければ、可能な限り対応いたします。建設的なご意見やご要望については検討いたしますが、単なる不平や苦情はご遠慮ください。**

*** 

* **Q:　macOSは、どのバージョンに対応していますか？**
* **A:　2024年度現在、Qt6.5以降に対応しており、macOS11（Big Sur）以降対応となります。[QtバージョンとmacOS対応](./Qt_vs_OS#macos)を参照ください。**

*** 

* **Q:　Apple Silicon Mac(MシリーズCPU搭載)で使用できますか？**
* **A:　使用可能です。Macユーザから動作報告を頂いています。下記のいずれかが必要です。**
  * **Rosetta2のインストールが必要**
  **[Mac に Rosetta をインストールする必要がある場合](https://support.apple.com/ja-jp/102527)**
  * **Apple Silicon版ffmpegが必要**
  **[AppleSilicon版ffmpegインストール手順](./install_mac_ffmpeg)**
  * **Apple Silicon版実行ファイルを使う**

*** 

* **Q:　Intel Mac(Intel製CPU搭載)で使用できますか？**
* **A:　使用可能です。Macユーザから動作報告を頂いています。**

*** 

* **Q:　TOPページにmacOS版の実行ファイルが掲載されていないのはなぜですか？macOS版実行ファイルはありますか？**
* **A:　[MacOSユーザの方へ](./macos)をご確認ください。リスクをご理解の上で自己解決できる方、動作確認にご協力頂ける方は最新版のリリースノートから実行ファイルを入手してください。**

*** 

* **Q:　どの実行ファイル（dmgファイル）を使用すれば良いですか？**
* **A:　通常は下記のファイル名の実行ファイルをご使用ください。「20yymmdd」はバージョンに対応した日付の数字です。**
  * **ファイル名:　CaptureStream2-MacOS-20yymmdd.dmg**
    * **その他、以下の文字列が含まれるファイル名の意味凡例**
    * **arm：Apple Silicon(Mシリーズ)向けを想定しています。**
    * **intel：intel Mac向けを想定しています。**
    * **qt5：古いmacOS(10.13 High Sierra)向けを想定しています。**
  

*** 

* **Q: 　macOS版で「開発元を検証できないため開けません。」とメッセージが出て、起動できません。**
* **A: 　macOSのバージョンによって操作方法が異なります。Apple Macユーザガイド[開発元が不明なMacアプリを開く](https://support.apple.com/ja-jp/guide/mac-help/mh40616/mac)でご使用のmacOSバージョンを選択して操作方法を確認ください。**

*** 

* **Q: 　Apple Mac App Storeへの公開予定はありますか？**
* **A: 　Apple Mac App Storeへの公開予定はありません。主に下記のような理由です。**
  * **Apple Developer Programへの登録が必要**
  * **Apple Developer Programは年間費用が必要**
  * **Mac実機が必要**
  * **Mac関連知識が乏しく、技量的に無理**
   
     * **尚、App Storeから入手されていない場合の対応はApple Macユーザガイド　[アプリがMac App Storeから入手されていない場合](https://support.apple.com/ja-jp/guide/mac-help/mh40620/mac)を参照してください。**

*** 

### **＜その他＞**
*** 

* **Q: 　モバイルOS（Android、iOS等）に対応していますか？**
* **A:　 対応していません。語学講座CS2は主要なDesktop OS（Windows、macOS、Linux）に対応していますが、Android、iOS等のモバイルOSには対応しておりません。Android、iOS向けアプリをご希望の方は[類似アプリ](./application)を参考にしてください。**

*** 

* **Q: 　対応するOSを教えてください。[必要要件](./requirements)に記載以外のOSでは使えませんか？**
* **A:　 語学講座CS2は主要なDesktop OS（Windows、macOS、Linux）に対応する、クロスプラットフォーム「Qt」で開発しています。[必要要件](./requirements)以外のOSでも動作する可能性はありますが、自己責任でお願いします。[必要要件](./requirements)以外であっても問題解決に向けて情報提供いただければ、可能な限り対応いたします。建設的なご意見やご要望については検討いたしますが、単なる不平や苦情はご遠慮ください。[QtとOSの対応](./Qt_vs_OS)もご確認ください。**

*** 



*** 
 <link rel="shortcut icon" type="image/x-icon" href="https://avatars.githubusercontent.com/u/46049273?v=4">
 <meta name="twitter:image:src" content="https://avatars.githubusercontent.com/u/46049273?v=4">
-
