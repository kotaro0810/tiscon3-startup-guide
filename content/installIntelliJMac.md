# IntelliJのインストール(Mac)

## 前提条件

* [Terminalを起動](tipsForMac.md#terminalの起動方法)して `java -version` とコマンドを入力した時、結果が返ってきますか？
* [Terminalを起動](tipsForMac.md#terminalの起動方法)して `mvn --version` とコマンドを入力した時、結果が返ってきますか？

## インストール

1. https://www.jetbrains.com/idea/#chooseYourEdition のDOWNLOADボタンから、**Community** のバージョンを選んでダウンロードしてください。
1. ダウンロードできたインストーラーを起動して、表示される手順に従ってインストールを進めてください。よくわからない項目はそのままYESを選択してください。


## プラグインの設定

1. もし起動していなかったら `Finder` > `アプリケーション` からIntelliJを起動し、`Configure` > `Plugins` を選択します。<br>
![プラグイン設定1](../image/intellij_top_settings.png)

1. `Browse repositories...` ボタンを押下します。<br>
![プラグイン設定2](../image/intellij_setting_plugins.png)

1. 検索バーに `Lombok` と入力し、Lombok Pluginを選択します。
右側に表示されるInstallボタンを押下してください。<br>
![プラグイン設定3](../image/intellij_setting_install_lombok-plugin.png)

## SDKの設定

1. Welcome画面で[Configure]→[Project Defaults]⇒[Project Structure]と選択してください。<br>
![SDK設定1](../image/intellij_top_project-structure_Mac.png)

1. [Project SDK]という見出しの下にあるプルダウンが＜No SDK＞になっていると思いますので、【New...】→【JDK】を選択してください。<br>
![SDK設定2](../image/intellij_setting_jdk1_Mac.png)

1. ご自身がインストールしたjdkの場所(/Library/Java/JavaVirtualMachines/jdk1.8.x_xxx.jdk)を選択して[OK]を押下してください。<br>
![SDK設定3](../image/intellij_setting_jdk1_select-home-directory_Mac.png)

1. Project SDKが設定され、【1.8(java version "1.8.x_xxx")】が選択されるかと思います。
一つ下の項目「Project language level」は「8 - Lambdas, type annotations etc.」を選択し、[OK]を押下してください。<br>
![SDK設定4](../image/intellij_setting_jdk2_Mac.png)
