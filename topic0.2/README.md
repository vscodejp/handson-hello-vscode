# Githubのリポジトリを VS Code で開こう

## このトピックでの目標
GithubのリポジトリをクローンしてVSCodeで表示すること

## Gitを使う準備をする
Gitをインストールしていない方は以下の手順でインストールを行ってください。

### Windows環境
[Git for Windows](https://gitforwindows.org/)からGitをダウンロードして実行する。

![](Git_for_Windows.PNG)

### Mac 環境

git コマンドを初めて実行したときに、XCode Command Line Tools のインストールを行うダイアログが表示されます。そのダイアログから、XCode Command Line Tools のインストールを進めてください。

どちらの環境でもすべてデフォルトの設定で問題ありません。

### ターミナルを開き、Gitがインストールされていることを確認する

VSCodeを開き、上部メニューバーの「ターミナル(T)」→「新しいターミナル」をクリックします。

![](Tarminal.PNG)

すると画面下部にターミナルが表示されます。

![](tarminal_gamen.PNG)

ターミナルで以下のコマンドを入力し、Versionが正しく表示されれば成功です。
```
git --version
```

成功例

![](git_version.PNG)

## GitubからリポジトリをCloneする

では、GitHubからリポジトリをCloneしてみましょう。

### Step1: クローンするリポジトリのGithubページを開く

以下のページを開きます。

[Hello VS Code ハンズオン 参加者向けガイド](https://github.com/vscodejp/handson-hello-vscode)

Githubのページで緑色の「Code」と書かれている部分をクリックします。

![](Code.PNG)

以下のようなホップアップが出てくるのでファイルマークをクリックし、cloneに利用するこのリポジトリのURLをコピーします。

![](Clone.PNG)

### Step2: リポジトリをcloneする

VSCodeを開き、上部メニューバーの「ターミナル(T)」→「新しいターミナル」をクリックします。

![](Tarminal.PNG)

すると画面下部にターミナルが表示されます。

![](tarminal_gamen.PNG)

表示されたターミナルで、以下のようにgit cloneコマンドを入力します。

```
git clone Step1でコピーしたURL
```

以下のようなメッセージが表示されれば、成功です。

![](terminal_seikou.PNG)

### Step2: cloneしたリポジトリをVSCodeで表示する

VSCodeの上記メニューバーで「ファイル」→「フォルダを開く」をクリックします。

Windowsの場合、以下のような画面が出るので先程Cloneしたフォルダである`handson-hello-vscode`を選択します。

![](open_foruda.png)

フォルダを開くと、以下のように`handson-hello-vscode`のリポジトリを VS Code で開くことができました。

画像のように左側にファイルツリーが表示されていれば成功です。

![](open.PNG)