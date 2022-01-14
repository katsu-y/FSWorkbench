# FSWorkbench
### Version 3.3

FSWorkbenchは、コンピュータのハードディスクなどローカルストレージ上のボリュームに含まれるファイルをGUIのリスト形式で表示・操作するアプリケーションです。

ファイルシステム関連の情報を表示する他、コピー,移動,削除など基本的な操作も行えます。

ドライブの割り当てられていないボリュームを参照することも出来ます。

ユーザーインターフェイスはMDI形式でTABを備えており、複数のファイルリストを表示できます。

通常はユーザーモードで使用できますが、管理者モードで実行した場合すべての機能が使用できます。

**注:** 現在FSWorkbenchはオープンソースではありません。

**NOTICE:** FSWorkbench is not open source. You will find here the builds only. 

### 実行環境

Windows 10,Windows 8.1,Windows 7
(64bit版/32bit版)

### インストール

適切な場所にディレクトリを作成し、書庫ファイルの内容を展開してください。<br>
【注意】<br>
 旧版FSDirWalkerを使用していた場合、同じ場所に展開しないでください。

### 実行方法
展開した場所から、FSWorkbench.exeを実行してください。

### アンインストール

現在、アンインストーラは用意されておりませんので、展開したファイルをユーザーご自身で削除してください。

現在はアンインストールしてもレジストリキーがそのままになります。気になる場合はご自身でキーを削除してください。
FSWorkbench自身が使用するレジストリキーは以下の通りです。
 (他にWindowsが他のレジストリパスに記録することがあります)

      HKEY_CURRENT_USER\Software\YamashitaSoftwareWorks\FSWorkbench

### 旧版からの移行

- FSDirWalker(前バージョン)のブックマーク、お気に入りをコピーしたい場合<br>
  `%LOCALAPPDATA%\FSTools\FSDirWalker`<br>
  内の `bookmarks.xml` と `favorites.xml` を<br>
  `%LOCALAPPDATA%\FSTools\FSWorkbench`  <br>
  にコピーしてください。

### 使用条件

本ソフトウェアは、下記条件を承諾の上であれば自由に無償で使用できます。

- 本ソフトウェアはご利用になる方の責任で使用してください。
  作者及び頒布者は本ソフトウェアの実行によって生じる結果に関して一切の責任を
  負いません。

- 本ソフトウェアを操作した結果データが失われたり、ソフトウェアが表示した内容，
  実行環境の差異，未知の不具合などが原因で損害が生じた場合でも、作者及び頒布者
  は一切の責任を負いません。

- 本ソフトウェアは自由に再頒布できますが、再頒布時は書庫ファイル内のファイル,
  ディレクトリ構成はそのままで変更しないでください。

- ソフトウェアの性質上、コンピュータ上のファイルの削除や属性の変更、コピーに
  よる内容の上書きなど、ファイルに対して不可逆な操作も行えますので十分注意し
  て使用してください。

- 不具合等の連絡は、下記メールアドレスなどよりお願いします。

- 本ソフトウェアの著作権は作者が留保します。

  Copyright (C) 2015-2021 山下 克宏 (YAMASHITA Katsuhiro), Yamashita Software Works
