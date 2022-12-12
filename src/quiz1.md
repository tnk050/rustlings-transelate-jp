# quiz1.rs

// このエクササイズは以下の章からなる問題です:
// - 変数
// - 関数
// - If

// メアリーはリンゴを買っているところです。リンゴ 1 個の値段は以下で計算します:

// - リンゴ 1 個の値段は 2 ラストドルです。
// - メアリーが 40 個よりも多くリンゴを買った場合、リンゴ 1 個の値段は 1 ラストドルになります!

// リンゴの購入数を入力すると値段を計算する関数を作成してください。今回はヒント無しです!

// I AM NOT DONE

```rust
// ここに関数を書いてください!
// fn calculate_price_of_apples {

// この関数は変更しないで!
#[test]
fn verify_test() {
    let price1 = calculate_price_of_apples(35);
    let price2 = calculate_price_of_apples(40);
    let price3 = calculate_price_of_apples(41);
    let price4 = calculate_price_of_apples(65);

    assert_eq!(70, price1);
    assert_eq!(80, price2);
    assert_eq!(41, price3);
    assert_eq!(65, price4);
}
```

<!---
// quiz1.rs
// This is a quiz for the following sections:
// - Variables
// - Functions
// - If

// Mary is buying apples. The price of an apple is calculated as follows:
// - An apple costs 2 rustbucks.
// - If Mary buys more than 40 apples, each apple only costs 1 rustbuck!
// Write a function that calculates the price of an order of apples given
// the quantity bought. No hints this time!

// I AM NOT DONE

// Put your function here!
// fn calculate_price_of_apples {

// Don't modify this function!
#[test]
fn verify_test() {
    let price1 = calculate_price_of_apples(35);
    let price2 = calculate_price_of_apples(40);
    let price3 = calculate_price_of_apples(41);
    let price4 = calculate_price_of_apples(65);

    assert_eq!(70, price1);
    assert_eq!(80, price2);
    assert_eq!(41, price3);
    assert_eq!(65, price4);
}
--->
