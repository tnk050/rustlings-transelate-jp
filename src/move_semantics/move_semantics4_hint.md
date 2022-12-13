# move_semantics4 hint

リファクタリングできると感じたらいつでも読むのを止めてください :)

もしくは 1 ステップずつ試してコンパイラのエラーを確認しながら修正してください!

クリアするためには:

- メイン関数の 1 行目、新しいベクタを生成している行を取り除いてください。
- すると`vec0`がいなくなり、`fill_vec`にベクタを渡せなくなります。
- `fill_vec`には何も渡したくないので、引数を取らないように変更します。
- メイン関数内では新しいベクタを作らないので、メイン関数で行ってきたのと同じように`fill_vec`内で新しいベクタを生成する必要があります。

<!---
Stop reading whenever you feel like you have enough direction :) Or try
doing one step and then fixing the compiler errors that result!
So the end goal is to:
   - get rid of the first line in main that creates the new vector
   - so then `vec0` doesn't exist, so we can't pass it to `fill_vec`
   - we don't want to pass anything to `fill_vec`, so its signature should
     reflect that it does not take any arguments
   - since we're not creating a new vec in `main` anymore, we need to create
     a new vec in `fill_vec`, similarly to the way we did in `main`
--->
