# HWFakeSafari

なんちゃってサファリを作ってみよう！

## 要件
#### 1.ストーリーボード上にはTextFieldを一つ、ボタンを一つ、WebViewを一つ設置する
#### 2.ボタンを押したらTextFieldに入力されたURLのページを、WebViewを使って表示する
#### 3.UserDefaultを使って、入力したURLを保存する
#### 4.一旦終了後、起動した時に前回表示したページが同じく表示されるようにする（初回はblank）

## POINT

 ※起動時にUserDefaultから前回表示したページのURLを取り出して表示処理を行うこと
 
 ※何もTextFieldに入力しないまま、ボタンを押したときはアラートを出したりラベルでメッセージを表示したり何か工夫して 空のURLをUserDefaultに保存しないようにしましょう
