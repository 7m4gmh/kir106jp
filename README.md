# Kir106jp - キルギス語（キリル文字） 日本語キーボード入力メソッド 
## Kir106jp - Kyrgyz tili phonetic input method for Japanese keyboard

キルギス語で使用されるキリル文字を日本語キーボードで入力するためのインプットメソッドです。
概ね、ラテン文字（ローマ字）の音と対応しています。

* 例外 [漢字 全/半] ъ 
* 例外 [q] ь
* 例外 [w] ш
* 例外 [x] ж
* 例外 [c] ч
* 例外 [y] ы
* 例外 [j] й など。

一部の文字は、２つ以上の文字を組み合わせて(続けて)入力します。
* 例: [^]+[o]= ө 
* 例: [^]+[n]= ң 
* 例: [o]+[^]= ө 
* 例: [n]+[^]= ң 
* 例: [j]+[e]= э 
* 例: [j]+[a]= я など。

シフトキーを押しながら上記の要領で入力すると、大文字を出します。
* 例: [J]+[a]= Я など。

このほかにも、多数の組み合わせがあります。
くわしくは、ソースファイル(kir106jp.klc)を参照。

## 対象システム
- Microsoft　Windows (32/62ビット- ia64, i386, amd64)

## インストール方法
* 圧縮済みのパッケージファイル(ZIPファイル)をダウンロード https://github.com/7m4gmh/kir106jp/archive/master.zip
* ZIPファイルを展開し、setup.exeを実行。

- インストールに成功すると、タスクバーのキーボード（入力メソッド）に、КЫРが表示されます。このアイコンをクリックすることで、キルギス語入力に切り替えます。

## ソースファイルについて
Microsoft Keyboard Layout Creator 1.4 でインストール用パッケージの作成が可能です。
* kir106jp.klc
