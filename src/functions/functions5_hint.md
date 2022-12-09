# functions5 hint

これは一文字だけの修正ですむとてもよくあるエラーです。

<!---
This is a really common error that can be fixed by removing one character.
It happens because Rust distinguishes between expressions and statements: expressions return a value based on their operand(s), and statements simply return a () type which behaves just like `void` in C/C++ language.
We want to return a value of `i32` type from the `square` function, but it is returning a `()` type...
They are not the same. There are two solutions:
1. Add a `return` ahead of `num * num;`
2. remove `;`, make it to be `num * num`
--->
