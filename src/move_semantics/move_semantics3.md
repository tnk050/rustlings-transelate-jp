# move_semantics3.rs

// 新しい行を追加せずに -- つまり既存の行を編集するだけでコンパイルを成功させてください!

// (一つの行に複数文を書く必要もありません!)

// `rustlings hint move_semantics3` コマンド、もしくは `rustlings watch` 中に `hint` コマンドを実行することによってヒントを表示することができます。

// I AM NOT DONE

```rust
fn main() {
    let vec0 = Vec::new();

    let mut vec1 = fill_vec(vec0);

    println!("{} の配列長は {} で、要素は `{:?}`", "vec1", vec1.len(), vec1);

    vec1.push(88);

    println!("{} の配列長は {} で、要素は `{:?}`", "vec1", vec1.len(), vec1);
}

fn fill_vec(vec: Vec<i32>) -> Vec<i32> {
    vec.push(22);
    vec.push(44);
    vec.push(66);

    vec
}
```

<!---
// move_semantics3.rs
// Make me compile without adding new lines-- just changing existing lines!
// (no lines with multiple semicolons necessary!)
// Execute `rustlings hint move_semantics3` or use the `hint` watch subcommand for a hint.

// I AM NOT DONE

fn main() {
    let vec0 = Vec::new();

    let mut vec1 = fill_vec(vec0);

    println!("{} has length {} content `{:?}`", "vec1", vec1.len(), vec1);

    vec1.push(88);

    println!("{} has length {} content `{:?}`", "vec1", vec1.len(), vec1);
}

fn fill_vec(vec: Vec<i32>) -> Vec<i32> {
    vec.push(22);
    vec.push(44);
    vec.push(66);

    vec
}
--->
