train.sh
Usage: $ bash train.sh (「wav + 話者番号」リスト)

1列目が wav ファイル、2列目が話者番号になっているリスト（列1と列2はタブ区切り）を入力して、
SVM を学習します。（モデルは ./SVM/model に保存されます）
入力する「wav + 話者番号」リストの形式は wavlist.txt を参考にして下さい。


test.sh
Usage: $ bash test.sh (wav ファイル) (結果の出力ディレクトリ)

wav ファイルを入力すると、./SVM/model に保存されている SVM のモデルを使って話者を推定します。
推定された話者番号がファイルに出力されます。



（メモ）
・UBM の場所
./UBM/jmodel
