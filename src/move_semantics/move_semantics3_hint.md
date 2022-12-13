# move_semantics3 hint

前回との違いは`fn fill_vec`内にあった`let mut vec = vec;`が無くなっていることです。

ある箇所に`mut`を追加して今ある不変な変数を可変にすることでこの行を追加する代わりにすることができます :)

<!---
The difference between this one and the previous ones is that the first line
of `fn fill_vec` that had `let mut vec = vec;` is no longer there. You can,
instead of adding that line back, add `mut` in one place that will change
an existing binding to be a mutable binding instead of an immutable one :)
--->
