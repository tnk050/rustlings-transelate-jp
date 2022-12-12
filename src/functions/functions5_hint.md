# functions5 hint

これはよく起こりがちな 1 文字だけの修正で済むエラーです。

このエラーは Rust が式と文を区別しているために起こります。式は自身のオペランドから成る値を返しますが、文はただ単に `()` の型を返します。ちょうど C/C++言語の`void`のようなものです。

`square`関数からは`i32`型の値を返したいのですが今は`()`型が帰ってしまっています...当然この 2 つは違う型です。

ここの解決法は 2 種類あります。

1. `return`を`num * num;`の前に書き加えます。
2. `num * num`となるように`;`を削除します。

<!---
This is a really common error that can be fixed by removing one character.
It happens because Rust distinguishes between expressions and statements: expressions return a value based on their operand(s), and statements simply return a () type which behaves just like `void` in C/C++ language.
We want to return a value of `i32` type from the `square` function, but it is returning a `()` type...
They are not the same. There are two solutions:
1. Add a `return` ahead of `num * num;`
2. remove `;`, make it to be `num * num`
--->
