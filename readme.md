# Fanuc-point-save

## 概要

教示点を記憶し、呼び出すことができます。

## point_save

TP プログラムにて、付加命令ｻｷｼﾞｯｺｳ ﾎﾟｲﾝﾄﾛｼﾞｯｸ 0.00s で、  
point_save を呼び出します。

### 引数 1

教示点から順番に 1,2,3,4...と整数系で指定します。

### 引数 2

各軸動作の場合には無しまたは 0、  
直線動作の場合には 1 を指定して下さい。

## point_load

point_save で登録した位置情報を呼び出し、  
戻り動作を行います。

## 設定変更

.kl 内の CONST 値を変更することで一部動作変更を行うことが出来ます。

## 更新履歴

## License

Released under the Apache 2.0 License.