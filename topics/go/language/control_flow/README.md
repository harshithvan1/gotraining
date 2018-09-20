## Control Flow

Control Flow in Go is similar to most C family languages but has some novel
differences. Classic structures like `if` and `switch` are present but their
syntax is a little different from what you might be used to.

There are no ternary operators.

## Notes

* `if` statements require an exact boolean expression. There is no "truthy" or "falsey".
* `if` statements may have a pre-expression similar to the first part of a `for` statement.
* `switch` statements do not require `break`s and will not fall through by default.
* `switch` statements can have multiple values per case.
* Use the `||` "or" and `&&` "and" operators for complex conditions.

## Code Review

[if statements](example1/example1.go) ([Go Playground](https://play.golang.org/p/djzGT1JtSwy))  
[switch statements](example2/example2.go) ([Go Playground](https://play.golang.org/p/09cxjnmfcdC))

## Exercises

### Exercise 1

Write a program that inspects a user's name and greets them in a certain way if
they are on a list or in a different way if they are not. Also look at the
user's age and tell them some special secret if they are old enough to know it.

[Template](exercises/template1/template1.go) ([Go Playground](https://play.golang.org/p/h-7BEn2U3Rz)) | 
[Answer](exercises/exercise1/exercise1.go) ([Go Playground](https://play.golang.org/p/eT_gLZKeHk-))
___
All material is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/LICENSE-2.0).