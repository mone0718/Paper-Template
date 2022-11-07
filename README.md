# LaTeXテンプレート

## 概要
LuaLaTeX と VSCode を使って論文を書くためのテンプレートです．
LuaLaTeX はフォントの設定が非常に簡単で，ソースの中に Lua のコードを利用できるのが特徴です．

## Mac向け環境構築

- このリポジトリを fork して clone
- MacTeXのインストール
```
brew install --cask mactex-no-gui 
```

- VSCode に拡張機能の LaTeX Workshop をインストール

以上で環境構築は終了です．Mac以外の環境は検証していませんが，LuaLaTeXが使えれば良いと思います．

## 使い方
- TeX ファイルを編集し，保存すると自動で PDFが /build にビルドされます
- option + command + B でも Tex ファイルをビルドできます
- option + command + V で PDF をプレビューできます

## 特徴
- 00_main.tex をビルドすると論文の全体がビルドされます
- 01_, 02_ から始まる章ごとのファイルも個別にビルドすることができます

### まだまだ作成途中です．
