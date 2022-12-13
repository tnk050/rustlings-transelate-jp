# move_semantics5 hint

同じスコープ内でそれぞれが可変参照する範囲には注意しなければなりません。

可変参照が取得された直後の x を参照先とした値の変更は上手くいくでしょうか?

「可変参照」のさらなる詳細は The Rust Programming Language の「参照と借用」から参照してください

"https://doc.rust-jp.rs/book-ja/ch04-02-references-and-borrowing.html#%E5%8F%AF%E5%A4%89%E3%81%AA%E5%8F%82%E7%85%A7"

<!---
Carefully reason about the range in which each mutable reference is in
scope. Does it help to update the value of referent (x) immediately after
the mutable reference is taken? Read more about 'Mutable References'
in the book's section References and Borrowing':
https://doc.rust-lang.org/book/ch04-02-references-and-borrowing.html#mutable-references.
--->
