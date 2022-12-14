# structs1.rs

// 全ての TODO を処理してテストをクリアしてください!

// `rustlings hint structs1` コマンド、もしくは `rustlings watch` 中に `hint` コマンドを実行することによってヒントを表示することができます。

// I AM NOT DONE

```rust
struct ColorClassicStruct {
    // TODO: ここにコードを書いてください
}

struct ColorTupleStruct(/* TODO: ここにコードを書いてください */);

#[derive(Debug)]
struct UnitLikeStruct;

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn classic_c_structs() {
        // TODO: クラシックなC言語型構造体をインスタンスしてください!
        // let green =

        assert_eq!(green.red, 0);
        assert_eq!(green.green, 255);
        assert_eq!(green.blue, 0);
    }

    #[test]
    fn tuple_structs() {
        // TODO: タプル構造体をインスタンスしてください!
        // let green =

        assert_eq!(green.0, 0);
        assert_eq!(green.1, 255);
        assert_eq!(green.2, 0);
    }

    #[test]
    fn unit_structs() {
        // TODO: ユニット様構造体をインスタンスしてください!
        // let unit_like_struct =
        let message = format!("{:?}s are fun!", unit_like_struct);

        assert_eq!(message, "UnitLikeStructs are fun!");
    }
}
```

<!---
// structs1.rs
// Address all the TODOs to make the tests pass!
// Execute `rustlings hint structs1` or use the `hint` watch subcommand for a hint.

// I AM NOT DONE

struct ColorClassicStruct {
    // TODO: Something goes here
}

struct ColorTupleStruct(/* TODO: Something goes here */);

#[derive(Debug)]
struct UnitLikeStruct;

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn classic_c_structs() {
        // TODO: Instantiate a classic c struct!
        // let green =

        assert_eq!(green.red, 0);
        assert_eq!(green.green, 255);
        assert_eq!(green.blue, 0);
    }

    #[test]
    fn tuple_structs() {
        // TODO: Instantiate a tuple struct!
        // let green =

        assert_eq!(green.0, 0);
        assert_eq!(green.1, 255);
        assert_eq!(green.2, 0);
    }

    #[test]
    fn unit_structs() {
        // TODO: Instantiate a unit-like struct!
        // let unit_like_struct =
        let message = format!("{:?}s are fun!", unit_like_struct);

        assert_eq!(message, "UnitLikeStructs are fun!");
    }
}
--->
