# Quarto を用いたプレゼンテーションテンプレート

以下の URL のコードを参考にしています。
https://github.com/quarto-dev/quarto-gallery/blob/main/presentations/powerpoint/powerpoint.qmd

こちらに他のテンプレートがあるので、そちらも参考にしてください。
https://quarto.org/docs/gallery/

## 使用方法

1. このリポジトリをクローン
2. Rstudio を入れる
3. VScode の拡張機能で Quarto を入れる
4. main.qmd を編集して、エディタ上の右上のボタンを押す
5. おそらくパッケージのインポートエラーが出るので、エラーで出たパッケージを Rstudio からインストールする
   `install.packages("rmarkdown")`など
6. 何度かインストールすると、エラーが出なくなるはず
7. ログに出力される URL をクリックして、パワーポイントをダウンロード
