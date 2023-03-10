# PlantUML Samples

2023年1月

### 環境構築

1. VSCode をインストールする。
2. Java Runtime Environment をインストールする。
   1. OracleJRE はインストールが必要なのでちょっと嫌  [Java | Oracle](https://www.java.com/ja/)
   2. OpenJDK は解凍のみで導入できる。 DevelopmentKit も含まれのが気持ち悪いがまぁOk。 [OpenJDK](https://openjdk.org/)
      - 今回は openjdk-19.0.1 を導入した
      - [Windows 版 OpenJDK インストール手順 - Qiita](https://qiita.com/ryo-sato/items/87d05021fcc0519e8828) を参考に環境変数 `JAVA_HOME` と `PATH` を編集する
3. Graphviz をインストールする。 [Graphviz](http://www.graphviz.org/)
4. VSCode拡張 PlantUML をインストールする。 （工場のアイコン）

### VSCode での使用方法

- 拡張子は **".pu"**

- プレビューの表示： **Alt + D**

- Pngファイル出力： コマンドパレット (Ctrl + Shift + P) → **PlantUML: Export Current Diagram**

  画像は  `./out/[filename]/[filename].png` に保存されました。

### PlantUML言語リファレンス

PlantUMLの文法は、"PlantUML Language Reference Guide" としてPDFファイルが提供されています。

https://plantuml.com/ja/guide



### References

[Visual Studio Code で UML を描こう！ - Qiita](https://qiita.com/couzie/items/9dedb834c5aff09ea7b2)

[Visual Studio Codeで自由自在にUMLを描こう - かずきのBlog@hatena](https://blog.okazuki.jp/entry/2016/09/01/215508)

[シンプルなテキストファイルで UML が書ける、オープンソースのツール](https://plantuml.com/ja/)

