# dajarep

[![GoDoc](https://godoc.org/github.com/kurehajime/dajarep?status.svg)](https://godoc.org/github.com/kurehajime/dajarep)

ダジャレを検索するコマンド

![dajarep](https://cloud.githubusercontent.com/assets/4569916/9517659/7641d0ca-4cec-11e5-98d6-7b0a64354877.gif)

駄洒落を含んだ文章ファイル(例:test.txt)を・・・

```
人民の人民による人民のための政治
アルミ缶の上にあるミカン
トンネルを抜けるとそこは雪国であった
智代子のチョコ
布団が吹っ飛んだ
我輩は猫である
猫が寝転んだ
その意見にはついていけん
靴を靴箱に入れる
傘を貸さない
イカは如何なものか
親譲りの無鉄砲で子供の時から損ばかりしている
```

dajarepに渡すと・・・

```
$ dajarep test.txt
```
駄洒落のみを抜き出します。
```
アルミ缶の上にあるミカン
智代子のチョコ
布団が吹っ飛んだ
猫が寝転んだ
その意見にはついていけん
傘を貸さない
イカは如何なものか
```

## インストール方法

[ここ](https://github.com/kurehajime/dajarep/releases)から実行ファイルをダウンロードできます。


Go言語の開発環境がある場合はgo でもインストールできます。

```
 go install github.com/kurehajime/dajarep/cmd/dajarep@v1.9.4
```

## オプション

-d	：掛かってる文字を表示  
-e  <エンコーディング>：エンコーディング指定  
-i	：インタラクティブモード  


## 解説記事

[文章からダジャレのみを抜き出すコマンドを作ってみた](http://qiita.com/kurehajime/items/a922d42dff5e0f03d32c)
