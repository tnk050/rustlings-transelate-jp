# move_semantics6.rs

// `rustlings hint move_semantics6` コマンド、もしくは `rustlings watch` 中に `hint` コマンドを実行することによってヒントを表示することができます。

// 参照の追加と削除以外は行わないでください。

// I AM NOT DONE

```rust
fn main() {
    let data = "Rustは偉大なり!".to_string();

    get_char(data);

    string_uppercase(&data);
}

// 所有権を持つべきではない
fn get_char(data: String) -> char {
    data.chars().last().unwrap()
}

// 所有権を持つべき
fn string_uppercase(mut data: &String) {
    data = &data.to_uppercase();

    println!("{}", data);
}
```

<!---
// move_semantics6.rs
// Execute `rustlings hint move_semantics6` or use the `hint` watch subcommand for a hint.
// You can't change anything except adding or removing references.

// I AM NOT DONE

fn main() {
    let data = "Rust is great!".to_string();

    get_char(data);

    string_uppercase(&data);
}

// Should not take ownership
fn get_char(data: String) -> char {
    data.chars().last().unwrap()
}

// Should take ownership
fn string_uppercase(mut data: &String) {
    data = &data.to_uppercase();

    println!("{}", data);
}
--->
