# move_semantics1 hint

13 行目のエラーで"cannot borrow immutable local variable `vec1` as mutable"

(不変の変数である`vec1`を可変のように借用できません。)と言われましたか?

これを直す方法はあるキーワードを追加することですが、エラーの出た 13 行目に追加するわけではありません。

追記: `fill_vec()`関数を呼び出した後に`vec0`にアクセスしようとすると何が起こるか試してみてください!

<!---
So you've got the "cannot borrow immutable local variable `vec1` as mutable" error on line 13,
right? The fix for this is going to be adding one keyword, and the addition is NOT on line 13
where the error is.
Also: Try accessing `vec0` after having called `fill_vec()`. See what happens!
--->
