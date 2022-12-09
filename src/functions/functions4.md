# functions4.rs

// `rustlings hint functions4` コマンド、もしくは `rustlings watch` 中に `hint` コマンドを実行することによってヒントを表示することができます。

// このお店では、値段が偶数のときに 10 ラストドルの割引を、

// 奇数のときに 3 ラストドルの割引を行っています。

// (この処理自体を疑問に思わないでください、今は関数の入出力のみに目を向けましょう。

// どちらかというと、これはこの先のエクササイズに向けての予行演習です!)

// I AM NOT DONE

```rust
fn main() {
    let original_price = 51;
    println!("売値は {}", sale_price(original_price));
}

fn sale_price(price: i32) -> {
    if is_even(price) {
        price - 10
    } else {
        price - 3
    }
}

fn is_even(num: i32) -> bool {
    num % 2 == 0
}
```

<!---
// functions4.rs
// Execute `rustlings hint functions4` or use the `hint` watch subcommand for a hint.

// This store is having a sale where if the price is an even number, you get
// 10 Rustbucks off, but if it's an odd number, it's 3 Rustbucks off.
// (Don't worry about the function bodies themselves, we're only interested
// in the signatures for now. If anything, this is a good way to peek ahead
// to future exercises!)

// I AM NOT DONE

fn main() {
    let original_price = 51;
    println!("Your sale price is {}", sale_price(original_price));
}

fn sale_price(price: i32) -> {
    if is_even(price) {
        price - 10
    } else {
        price - 3
    }
}

fn is_even(num: i32) -> bool {
    num % 2 == 0
}
--->
