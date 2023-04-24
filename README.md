## Overview

以下のことが学べるかもしれません
* PublisherとSubscliberの書き方・扱い方
* parameterの設定方法
* launchファイルの書き方（Python）
* launchファイルを使った場合のparameter（yaml）の設定方法
* Github Actionの設定方法
* READMEの書き方

## 以下に課題内容と使用するコマンドを示す

### 課題１
自分の名前を0.5秒ごとにパブリッシュ（10回に一回は池邉さんの名前）し、
サブスクライブして名前を標準出力するros2パッケージを作る。  
パッケージ名「myname_pubsub」プライベートリポジトリで作る。  
プロセスのcppファイルは一つのみ

### 課題２
ROS 2にはパラメータがあるのですが今のプログラムで、ros2 param set /myname_pubsub/pub_rate 1.0を実行した時に周期が1秒になるようにしてみてください。

### 課題３
課題2のプログラムをpythonのlaunchファイルで立ち上げる 

### 課題４
パッケージにconfigフォルダを作成し、mayname_pubsub.param.yamlを作成し、そこにpub_nameとpub_rateというパラメータを書きます。  
それをlaunchファイルでnodeのパラメータとして読み込むように書いてください。

### 課題５
GitHub Actionsを使い、パッケージのビルドが問題ないことを示しましょう。

### 最終課題
良い感じにREADMEを作成してください。