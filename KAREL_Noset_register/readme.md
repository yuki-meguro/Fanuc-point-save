# 概要

point_save.kl と point_load.kl 間の通信でレジスタを使わずやり取りができます。

# point_save

## 引数 1

教示点から順番に 1,2,3,4...と整数系で指定します。

## 引数 2

各軸動作の場合には無しまたは 0、
直線動作の場合には 1 を指定して下さい。

# point_load

point_save で登録した位置情報を呼び出し、  
戻り動作を行います。

# License

Released under the Apache 2.0 License.
