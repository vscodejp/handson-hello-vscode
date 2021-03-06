# GitHub のリポジトリを VS Code で開こう

## このトピックでの目標

GitHub のリポジトリをクローンして VS Code で表示できるようになる

## Git を使う準備をする

Git をインストールしていない方は以下の手順でインストールを行ってください。
Windows / macOS どちらの環境でもすべてデフォルトの設定で問題ありません。

### Windows 環境

[Git for Windows](https://gitforwindows.org/)から Git のインストーラーをダウンロードし、インストールを行ってください。

![](img/Git_for_Windows.PNG)

### macOS 環境

#### ターミナルを開き、Git がインストールされていることを確認する

VS Code を開き、画面上部にあるメニューバーの`ターミナル`→`新しいターミナル`をクリックします。

![](img/Tarminal.PNG)

すると画面下部にターミナルが表示されます。

![](img/tarminal_gamen.PNG)

ターミナルで以下のコマンドを入力し、Git のバージョンが正しく表示されれば OK です。

```bash
git --version
```

![](img/git_version.PNG)

**macOS** の場合、環境によっては `コマンドライン・デベロッパ・ツール` のインストールが求められる場合があります。
以下のような画面が表示された場合は、コマンドライン・デベロッパ・ツールを**インストール**するようにしてください。

![](img/check_install_xcode_dev_tools.png)

## GitHub からリポジトリをクローンする

では、GitHub からリポジトリをクローンしてみましょう。

### Step1: クローンするリポジトリの GitHub ページを開く

ブラウザで、以下のページにアクセスします。

- [Hello VS Code ハンズオン 参加者向けガイド](https://github.com/vscodejp/handson-hello-vscode)

GitHub のページで緑色の `Code` と表示されているボタンを**選択**します。

![](img/Code.PNG)

以下のようなホップアップが表示されるので、赤枠の部分にある`クリップボード`のボタンを**選択**し、Git でこのリポジトリをクローンするための URL を**コピー**します。

![](img/Clone.PNG)

### Step2: リポジトリをクローンする

VS Code を起動し、画面上部にあるメニューバーの`ターミナル`→`新しいターミナル`を**選択**します。

![](img/Tarminal.PNG)

すると画面下部にターミナルが表示されます。

![](img/tarminal_gamen.PNG)

表示されたターミナル内にて、下記のコマンドを入力します。
\<Step1 でコピーした URL\> は、Step1 で取得した URL に置き換えてください。

```
git clone <Step1でコピーしたURL>
```

以下のようなメッセージが表示されれば、OK です。

![](img/terminal_seikou.PNG)

### Step3: クローンしたリポジトリを VS Code で表示する

VS Code の画面上部にあるメニューバーの`ファイル`→`フォルダを開く`を**選択**します。

Windows 環境の場合、以下のような画面が出るため、先程クローンしたフォルダである`handson-hello-vscode` を**選択**します。

![](img/open_foruda.png)

フォルダを開くと、以下のように `handson-hello-vscode` のリポジトリを VS Code で開くことができます。
フォルダの内容が画面左部にあるファイルツリーに表示されていれば OK です。

![](img/open.PNG)
