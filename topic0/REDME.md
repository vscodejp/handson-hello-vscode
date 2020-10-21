# VS Code のインストールしよう

公式ドキュメント https://code.visualstudio.com/docs/setup/setup-overview

## Visual Studio Code をインストールしよう

公式サイト https://code.visualstudio.com/ より、Download してください。

### Windows の場合

インストーラがダウンロードされるため、実行します。

この時 code コマンドをインストールするか尋ねる選択肢「Add to Path」が表示されるため、チェックを入れてインストールを進めます。

### macOS の場合

zip ファイルがダウンロードされるため、解凍して、出てきたアプリ Code を、/Applications ディレクトリにコピーします。

一度 Visual Studio Code を起動し、F1 キーを押してコマンドパレットを開き、コマンド ”Shell Command: Install 'code' Command in PATH”を実行します。

### Linux の場合

RPM パッケージ、deb パッケージの他、Snap Store、apt リポジトリで提供されています。
Snap Store、apt リポジトリの場合は、パッケージシステムを利用してアップデートを行うことができます。

https://code.visualstudio.com/docs/setup/linux

## 表示言語に日本語を設定しよう

初期状態では、メニューの言語は英語であるため、日本語メニューに変更したい場合、この手順を進めてください。
本ハンズオンでは、表示言語が日本語であることを前提に進めます。

- (1) アクティビティーバー（画面左端のタブメニュー）から拡張機能タブを押します。
- (2) サイドバー（画面左側のエリア）の、"Search Extions in Marketplace" に "japanease" と入力します。
- (3) サイドバー中に "Japanese Language Pack for Visual Studio Code" という項目が出てくるので、その中の "install" ボタンを押します。
- (4) 通知ポップアップ（画面右下）に "Would you like to change VS Code's UI language to Japanese and restart?" と表示されるため、"Yes"を押します。
- (5) 再起動を促すポップアップが表示されるため、"Restart"を押します。

ポップアップを閉じてしまったり、表示されない場合は、F1 キーを押してコマンドパレットを開き、コマンド"Configure Display Language"を選び、続いて表示される選択肢で"ja"を選びます。
