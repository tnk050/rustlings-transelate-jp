# primitive_types4 hint

The Rust Programming Language から 所有権を理解する → スライス型 → 他のスライス を確認してください。

"https://doc.rust-jp.rs/book-ja/ch04-03-slices.html"

そしてあなたが欲しい配列になるように開始と終了を指定してください。

もしあなたが`assert_eq!`の第二引数が参照であるのに第一引数に`&`修飾子がついていないことを

奇妙に感じた場合は Rust 裏本の 型強制 を読んでみてください。

"https://doc.rust-jp.rs/rust-nomicon-ja/coercions.html"

<!---
Take a look at the Understanding Ownership -> Slices -> Other Slices section of the book:
https://doc.rust-lang.org/book/ch04-03-slices.html
and use the starting and ending indices of the items in the Array
that you want to end up in the slice.
If you're curious why the first argument of `assert_eq!` does not
have an ampersand for a reference since the second argument is a
reference, take a look at the coercion chapter of the nomicon:
https://doc.rust-lang.org/nomicon/coercions.html
--->
