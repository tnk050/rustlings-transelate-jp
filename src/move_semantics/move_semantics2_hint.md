# move_semantics2 hint

`vec0`は`fill_vec`関数の引数として取られています。

Rust では引数として渡した値を明示的に返さない限り、再度使用することはできません。

私たちはこのことを変数の「ムーブ」と呼んでいます。

関数(もしくはブロックスコープ)に渡された変数で明示的に返されないものは関数の終点で「ドロップ」されます。

これはこのエクササイズでも起こっていることです。

これにはいくつかの解決策があります、よければ全て試してみましょう:

1. もう一つ別の`vec0`を作成して`fill_vec`へ代わりに渡します。
2. `fill_vec`の引数の取り方をムーブから借用にします。そして新しい`Vec<i32>`を返すために関数内でコピーします。
3. `fill_vec`の引数を可変な参照として借用し(その場合、引数も可変にする必要が有るでしょう)、直接変更して何も返さずに終了します。
   そしてエクササイズから`vec1`を取り除きます。 --注)この場合、最初の`println!`が変化することでしょう。

<!---
So, `vec0` is passed into the `fill_vec` function as an argument. In Rust,
when an argument is passed to a function and it's not explicitly returned,
you can't use the original variable anymore. We call this "moving" a variable.
Variables that are moved into a function (or block scope) and aren't explicitly
returned get "dropped" at the end of that function. This is also what happens here.
There's a few ways to fix this, try them all if you want:
1. Make another, separate version of the data that's in `vec0` and pass that
   to `fill_vec` instead.
2. Make `fill_vec` borrow its argument instead of taking ownership of it,
   and then copy the data within the function in order to return an owned
   `Vec<i32>`
3. Make `fill_vec` *mutably* borrow a reference to its argument (which will need to be
   mutable), modify it directly, then not return anything. Then you can get rid
   of `vec1` entirely -- note that this will change what gets printed by the
   first `println!`
--->
