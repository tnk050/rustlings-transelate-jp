# primitive_types6.rs

// インデックスを使用して`numbers`の 2 番目の要素にアクセスしてください。

// テストをクリアするため ??? が要素の 2 番目になるよう式を書きましょう。

// `rustlings hint primitive_types6` コマンド、もしくは `rustlings watch` 中に `hint` コマンドを実行することによってヒントを表示することができます。

// I AM NOT DONE

```rust
#[test]
fn indexing_tuple() {
    let numbers = (1, 2, 3);
    // 下の ??? をタプルとインデックスの式に置き換えてください
    let second = ???;

    assert_eq!(2, second,
        "これはタプルの2番目じゃありません!")
}
```

<!---
// primitive_types6.rs
// Use a tuple index to access the second element of `numbers`.
// You can put the expression for the second element where ??? is so that the test passes.
// Execute `rustlings hint primitive_types6` or use the `hint` watch subcommand for a hint.

// I AM NOT DONE

#[test]
fn indexing_tuple() {
    let numbers = (1, 2, 3);
    // Replace below ??? with the tuple indexing syntax.
    let second = ???;

    assert_eq!(2, second,
        "This is not the 2nd number in the tuple!")
}
--->
