# move_semantics6 hint

答えを見つけたければ The Rust Programming Language の「参照と借用」を読み込むと良いでしょう。

"https://doc.rust-jp.rs/book-ja/ch04-02-references-and-borrowing.html"

最初の問題は`get_char`が文字列の所有権を取得していることです。

`data`が`get_char`へムーブしているため`string_uppercase`で使用できない、つまり`string_uppercase`は文字列を操作できないということになっています。

それを修正しようとすると`string_uppercase`関数のシグネチャも合わせて変更する必要があるでしょう。

どうすれば良いかわかりますか?

別のヒント: `&`修飾子が必要になります。

<!---
To find the answer, you can consult the book section "References and Borrowing":
https://doc.rust-lang.org/stable/book/ch04-02-references-and-borrowing.html
The first problem is that `get_char` is taking ownership of the string.
So `data` is moved and can't be used for `string_uppercase`
`data` is moved to `get_char` first, meaning that `string_uppercase` cannot manipulate the data.
Once you've fixed that, `string_uppercase`'s function signature will also need to be adjusted.
Can you figure out how?
Another hint: it has to do with the `&` character.
--->
