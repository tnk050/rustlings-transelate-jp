# ベクタ

ベクタは Rust でもっともよく使われるデータ構造の一つです。

他のプログラミング言語では単に配列となっていますが、Rust では低レベルの操作を行うため

配列はスタックに値を保持し(つまり縮小も拡大もできず、コンパイル時にサイズが決まっている必要があります)、

ベクタはヒープに値を保持します(ヒープでは上記の制限は適用されません)。

ベクタは The Rust Programming Language ではもう少し後ろの章で説明されています、

けれども私たちはベクタがとても有用であるため先に説明すべきだと考えます。

もう一つのパワフルなデータ構造 ハッシュマップ については後ほど説明させてください。

## 詳細

- [ベクタで値のリストを保持する](https://doc.rust-jp.rs/book-ja/ch08-01-vectors.html)

<!---
# Vectors

Vectors are one of the most-used Rust data structures. In other programming
languages, they'd simply be called Arrays, but since Rust operates on a
bit of a lower level, an array in Rust is stored on the stack (meaning it
can't grow or shrink, and the size needs to be known at compile time),
and a Vector is stored in the heap (where these restrictions do not apply).

Vectors are a bit of a later chapter in the book, but we think that they're
useful enough to talk about them a bit earlier. We shall be talking about
the other useful data structure, hash maps, later.

## Further information

- [Storing Lists of Values with Vectors](https://doc.rust-lang.org/stable/book/ch08-01-vectors.html)
--->
