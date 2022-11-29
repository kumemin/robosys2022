![test](https://github.com/kumemin/robosys2022/actions/workflows/test.yml/badge.svg)

# robosys2022
* ロボットシステム学の練習用のリポジトリです。
* インストール方法
```
$ git clone https://github.com/kumemin/robosys2022
$ cd robosys2022
```

## 必要なソフトウェア
* Python
  * テスト済み:Python 3.7〜3.10
* OS
  * Ubuntu
    * [ダウンロード](https://jp.ubuntu.com/download)

## 動作確認済み環境
* Ubuntu18.04

# plusコマンド
標準入力から読み込んだ数字の和とその2進数表示と16進数表示
* [plus](https://github.com/kumemin/robosys2022/blob/main/plus)
* 使い方:seq 5 | ./plus と入力
```
$ seq 5 | ./plus #5の部分は任意の正の整数、または小数を入力
15 0b1111 0xf # 1 + 2 + ... + 5 の和。またその和の2進数表示と16進数表示
```
## LICENSE
* このソフトウェアパッケージは，三条項BSDライセンスの下，再配布および使用が許可されています．
* このパッケージは，aaa由来のコード（© 2022 Hoge Fuge）を利用しています．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
  * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Mizuki Kume
