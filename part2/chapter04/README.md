# 概要
demoディレクトリが、Spring BootアプリケーションのGradleプロジェクトとなっています。  
IntelliJ IDEAで [File]->[Open] を選択し、このディレクトリのbuild.gradle.ktsを開いてください。  
ダイアログが表示されるので、[Open as Project] を選択してください。

4章の内容で作成したクラスごとにファイルがあり、それぞれ追加されていった関数、処理が全て入った状態のものになっています。

# 実行方法
書籍内で解説しているものと同様、以下の方法で実行できます。

- IntelliJ IDEAのGradleビューから、[Tasks]->[application]->[bootRun]を実行
- ターミナルでdemoディレクトリから ```./gradlew bootRun``` を実行
- DemoApplication.ktのmain関数を実行

# 補足
複数のリストで同じクラス名や関数名を使っている場合など、並べて書かれているとコンパイルエラーになってしまうものは、コメントアウトされています。  
必要に応じてコメントを外し、実行してください。  
コンパイルエラーになる例を紹介しているコードに関しても、同様にコメントアウトされています。