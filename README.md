# Python基本構文
この課題は初学者さん用に基礎文法の理解度チェックするためのものです。  
ある程度理解している方は飛ばしてもかまいません。  
わからないところは、調べて自己解決できる力をつけましょう！  
どうしてもわからない場合はご質問ください。

## task1. 変数の使い方

```
name1 :str = "シンジ"
name2 :str = "カヲルくん"
```

変数を定義するときは、変数名のあとに型(今回だと文字列なので:str)をつけましょう。  
複雑なコードになると変数の中に何が入っているか明確化されている方がメンテナンス性が上がります。  
複数人開発時に他の人が見てコードが読みやすくなります。

変数を使って、  
```
シンジとカヲルくんは仲良し！
```
とprint文を使って表示させましょう。

## task2. if文の使い方

task1のソースを改造して、name2が**使徒**だった場合に
```
使徒です！
```
とprint文で表示させましょう。

## task3. 配列の使い方

```
names: list = ["シンジ", "レイ", "カヲルくん"]
```

上記の配列に、「アスカ」を追加しましょう。

## task4. for文の使い方

task3のソースコードを使用し、`names`のキャラクターをfor文を使って1行に1キャラずつ表示してみましょう。

## task5. 関数の使い方

task4で作ったコードを関数にしましょう。  
関数化したら、その関数を呼び出して結果が表示されることを確認しましょう。

## task6. 引数を使う関数の使い方

task5で作成した関数の引数に「マリ」を渡して、`names`に追加しましょう。  
リストに追加されているか表示されることを確認しましょう。

関数、引数に関しては、[こちら](https://www.mathpython.com/ja/type/)を参考にしてみましょう。

## task7. 文字検索

```
name = input("名前を入力してください：")
```
上記で、入力した文字列を`name`に代入しましょう。
if文で`in`を使い、入力した名前が`names`の中に含まれているか判定しましょう。
含まれている場合は「{入力した名前}はいます。」、
含まれてない場合は「{入力した名前}はいません。」と表示させましょう。

`in`については[こちら](https://ai-inter1.com/python-if-in/)を参考にしてみましょう。
