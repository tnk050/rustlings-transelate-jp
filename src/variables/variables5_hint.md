# variables5_hint

`variables4`で変数を可変にする特別なキーワードを学びました。

しかし残念なことに、既にある変数に違う型の値を代入しようとしているためこのキーワードは役に立ちません。

時々、このエクササイズのように変数名を使いまわして値の変換を行いたい場合があるかもしれません。

こんなこともあろうかと、Rust にはこの問題を解決するパワフルな手法があります。「シャドーイング」です!

シャドーイングについての詳細は The Rust Programming Language の「変数と可変性」を参照してください。

"https://doc.rust-jp.rs/book-ja/ch03-01-variables-and-mutability.html#%E3%82%B7%E3%83%A3%E3%83%89%E3%83%BC%E3%82%A4%E3%83%B3%E3%82%B0"

このテクニックを使用してエクササイズを成功させましょう。

<!---
In variables4 we already learned how to make an immutable variable mutable
using a special keyword. Unfortunately this doesn't help us much in this exercise
because we want to assign a different typed value to an existing variable. Sometimes
you may also like to reuse existing variable names because you are just converting
values to different types like in this exercise.
Fortunately Rust has a powerful solution to this problem: 'Shadowing'!
You can read more about 'Shadowing' in the book's section 'Variables and Mutability':
https://doc.rust-lang.org/book/ch03-01-variables-and-mutability.html#shadowing
Try to solve this exercise afterwards using this technique.
--->
