# GoLang FAQ

## Table of Contents
1. [What is the static variable declaration in Golang?](#1-what-is-the-static-variable-declaration-in-golang)
2. [What is the dynamic variable declaration in Golang?](#2-what-is-the-dynamic-variable-declaration-in-golang)
3. [What is swapping in variables and How can we swap variables in Golang?](#3-what-is-swapping-in-variables-and-how-can-we-swap-variables-in-golang)
4. [What are packages in Golang?](#4-what-are-packages-in-golang)
5. [Is Go case sensitive?](#5-is-go-case-sensitive)
6. [What is main Package in Go?](#6-what-is-main-package-in-go)
7. [Can we access main package from other package?](#7-can-we-access-main-package-from-other-package)
8. [What is a constant variable in Go?](#8-what-is-a-constant-variable-in-go)
9. [Different ways to declare a variable in go?](#9-different-ways-to-declare-a-variable-in-go)
10. [Can we return multiple values from a function?](#10-can-we-return-multiple-values-from-a-function)
11. [What is a struct in golang ?](#11-what-is-a-struct-in-golang-)
12. [Explain Methods and functions in Golang ?](#12-explain-methods-and-functions-in-golang-)
13. [Explain If GoLang is fast?](#13-explain-if-golang-is-fast)
14. [How can we declare the multiple types of variables in a single code line in Golang?](#14-how-can-we-declare-the-multiple-types-of-variables-in-a-single-code-line-in-golang)
15. [What are built-in supports in Golang?](#15-what-are-built-in-supports-in-golang)
16. [What is slice in Golang?](#16-what-is-slice-in-golang)
17. [What are the decision-making statements in Golang?](#17-what-are-the-decision-making-statements-in-golang)
18. [What is the GoPATH variable in Golang?](#18-what-is-the-gopath-variable-in-golang)
19. [What is the GoROOT variable in Golang?](#19-what-is-the-goroot-variable-in-golang)
20. [What is GOBIN variable in golang?](#20-what-is-gobin-variable-in-golang)
21. [Explain break statement in Golang?](#21-explain-break-statement-in-golang)
22. [Explain continue in GO?](#22-explain-continue-in-go)
23. [Exlain Labels in Golang?](#23-exlain-labels-in-golang)
24. [Explain GOTO in golang?](#24-explain-goto-in-golang)
25. [Can you have Switch Case with Break in GO?](#25-can-you-have-switch-case-with-break-in-go)
26. [Do we have to use BREAK in golang switch case?](#26-do-we-have-to-use-break-in-golang-switch-case)
27. [Can we use default in golang switch case?](#27-can-we-use-default-in-golang-switch-case)
28. [What is fallthrough in Golang?](#28-what-is-fallthrough-in-golang)
29. [What are Golang string literals?](#29-what-are-golang-string-literals)
30. [What do you understand by the scope of variables in Go?](#30-what-do-you-understand-by-the-scope-of-variables-in-go)
31. [What are function closures or anonymous functions in golang?](#31-what-are-function-closures-or-anonymous-functions-in-golang)
32. [Can you format a string without printing in golang?](#32-can-you-format-a-string-without-printing-in-golang)
33. [What is Type Assertion in Go?](#33-what-is-type-assertion-in-go)
34. [What is the use of Type Assetion in Golang?](#34-what-is-the-use-of-type-assertion-in-golang)
35. [Does golang supports automatic or implicit Type Casting or Type Conversion?](#35-does-golang-supports-automatic-or-implicit-type-casting-or-type-conversion)
36. [How to check the variable type at runtime in Golang?](#36-how-to-check-the-variable-type-at-runtime-in-golang)
37. [How to compare two structs in golang?](#37-how-to-compare-two-structs-in-golang)
38. [How to compare two maps in golang?](#38-how-to-compare-two-maps-in-golang)
39. [Can we have exceptions in Golang?](#39-can-we-have-exceptions-in-golang)
40. [What is defer and panic in Golang?](#40-what-is-defer-and-panicin-golang)
41. [Explain pointers in Go?](#41-explain-pointers-in-go)
42. [What are Goroutines?](#42-what-are-goroutines)
43. [What are anounymous Go Routines ?](#43-what-are-anounymous-go-routines-)
44. [What are waitgroups in Go?](#44-what-are-waitgroups-in-go)
45. [What is a receive operator in Go?](#45-what-is-a-receive-operator-in-go)
46. [What are channels in Go?](#46-what-are-channels-in-go)
47. [What is a unidirectional channel in Go ?](#47-what-is-a-unidirectional-channel-in-go-)
48. [How to declare a channel as a ValueType or Reference Type seperatly ?](#48-how-to-declare-a-channel-as-a-valuetype-or-reference-type-seperatly-)
49. [Should we use go routines in a program with Global variables?](#49-should-we-use-go-routines-in-a-program-with-global-variables)
50. [Access Modifiers in Go?](#50-access-modifiers-in-go)
51. [Can we access an unexported variable of a package in another package in GO ?](#51-can-we-access-an-unexported-variable-of-a-package-in-another-package-in-go-)

### 1. What is the static variable declaration in Golang?
Static variable declaration in Golang:
```go
var staticVariable int
```

### 2. What is the dynamic variable declaration in Golang?
Dynamic variable declaration in Golang:
```go
dynamicVariable := 42
```

### 3. What is swapping in variables and How can we swap variables in Golang?
Swapping variables in Golang:
```go
a, b := 1, 2
a, b = b, a
//or
number3 = number1
number1 = number2
number2 = number3

```

### 4. What are packages in Golang?
Packages in Golang are a way to organize and reuse code.

### 5. Is Go case sensitive?
Yes, Go is case-sensitive.

### 6. What is main Package in Go?
The main package is the entry point of a Go program and contains the `main` function.

### 7. Can we access main package from other package?
No, accessing the main package from another package in Go is not possible.

### 8. What is a constant variable in Go?
Constant variable in Go:
```go
const pi = 3.14
```

### 9. Different ways to declare a variable in go?
Different ways to declare a variable in Go:
`var`, `:=`, `const`.
```go
//Explicit Declaration
var a int
var b, c int
var d, e, f string = "A", "B", "C"
var (
	l int
	m string
	n int
	)
var (
    l int    = 1
	m string = "A"
	n int    = 0
	)
var g int = 10
// Implicit declaration and initialization
h := "Mark"
var i, j, k = 10, 20.10, "test" 
```

### 10. Can we return multiple values from a function?
Yes, we can return multiple values from a function in Go. Example:
```go
func swap(a, b int) (int, int) {
    return b, a
}
```

### 11. What is a struct in Golang?
A struct in GoLang is a composite data type that groups together variables of different types under a single name.

Example:
```go
type Person struct {
    Name string
    Age  int
}
```

### 12. Explain Methods and functions in Golang?
Functions in GoLang are blocks of code that perform a specific task. Methods are functions associated with a type.
```go 
func (m methodEx) methodInGo() {
	fmt.Println(m)
}

func funcInGo() {
	fmt.Println("I am function in Go")
}
```

### 13. Explain If GoLang is fast?
Yes, GoLang is known for its speed due to its efficient concurrency model and optimized compilation process.

### 14. How can we declare the multiple types of variables in a single code line in Golang?
We can declare multiple types of variables in a single line in GoLang using the var keyword:

Example:
```go
var x, y int = 1, 2
```

### 15. What are built-in supports in Golang?
Built-in supports in Golang include various data types, control structures, and functions.

### 16. What is slice in Golang?
A slice in GoLang is a Dynamic array with flexible size.

### 17. What are the decision-making statements in Golang?
Decision-making statements in GoLang include if, switch, and select.

### 18. What is the GoPATH variable in Golang?
Path to workspace.The GOPATH variable in GoLang specifies the location of the workspace.

### 19. What is the GoROOT variable in Golang?
Path to Go installation.The GOROOT variable in GoLang specifies the root of the Go installation.

### 20. What is GOBIN variable in Golang?
Path to Go binary files.
The GOBIN variable in GoLang specifies the directory where compiled binaries will be installed.

### 21. Explain break statement in Golang?
Exit loop or switch.
The break statement in GoLang is used to terminate the execution of the innermost loop (for, switch, or select) and resume execution at the next statement after the loop.

### 22. Explain continue in Go?
Skip current iteration and continue loop.
The continue statement in GoLang is used to skip the rest of the current iteration of a loop and continue to the next iteration.

### 23. Explain Labels in Golang?
Marker for goto statements.
Labels in GoLang are identifiers followed by a colon that are used to mark a position in the code. They are primarily used with break and continue statements to control the flow of execution.

### 24. Explain GOTO in Golang?
Jump to a labeled statement.
```go 
func Labels() {
	fmt.Println(1)
	goto End
	fmt.Println(2)
End:
	fmt.Println(3)
}
```
GOTO is a statement in GoLang that allows jumping to a labeled statement in the code. However, GOTO is not recommended for use in most cases due to its potential to create unreadable and unmaintainable code.

### 25. Can you have Switch Case with Break in GO?
In GoLang, the switch statement automatically breaks after executing a case block. There's no need for an explicit break statement after each case block.
```go 
func switchWithBreak() {
forLoop:
	for number := 1; number < 10; number++ {
		fmt.Printf("%d", number)
		switch {
		case number == 1:
			fmt.Println("I am One")
		case number == 2:
			fmt.Println("I am Two")
		case number == 3:
			fmt.Println("I am Three")
		case number == 4:
			fmt.Println("I am Four")
		case number == 5:
			fmt.Println("I am Five")
		case number == 6:
			fmt.Println("I am Six")
		case number > 2:
			fmt.Println("I am Greater than two")
			break forLoop
		case number == 8:
			fmt.Println("I am Eight")
		case number == 9:
			fmt.Println("I am Nine")
		default:
			fmt.Println("I am Number that is not identified")
		}
	}
}
```



### 26. Do we have to use BREAK in Golang switch case?
No, in GoLang, the switch statement automatically breaks after executing a case block, so there's no need for an explicit break statement.

```go 
func switchWithBreak() {
forLoop:
	for number := 1; number < 10; number++ {
		fmt.Printf("%d", number)
		switch {
		case number == 1:
			fmt.Println("I am One")
		case number == 2:
			fmt.Println("I am Two")
		case number == 3:
			fmt.Println("I am Three")
		case number > 2:
			fmt.Println("I am Greater than two")
			break forLoop
		case number == 8:
			fmt.Println("I am Eight")
		default:
			fmt.Println("I am Number that is not identified")
		}
	}
}
```

### 27. Can we use default in Golang switch case?
Yes, the default case in GoLang switch statements is optional. It is executed when none of the other case expressions match the switch expression.

### 28. What is fallthrough in Golang?
Continue to next case in switch.
The fallthrough statement in GoLang is used to transfer control to the first statement of the next case block in a switch statement, regardless of whether the expression matches.

### 29. What are Golang string literals?
String literals in GoLang are a sequence of characters enclosed in double quotes (""). They represent string values in GoLang.

### 30. What do you understand by the scope of variables in Go?
The scope of a variable in GoLang refers to the region of code where the variable is accessible. Variables declared inside a function are scoped to that function, while variables declared outside of any function have package-level scope.

### 31. What are function closures or anonymous functions in GoLang?
Function closures or anonymous functions in GoLang are functions defined without a name.They can capture variables from outer scope.They are often used for short, simple operations and can be assigned to variables or passed as arguments to other functions.

Example:
```go
func main() {
    add := func(x, y int) int {
        return x + y
    }

    result := add(3, 4) // result will be 7
}
```

### 32. Can you format a string without printing in GoLang?
Yes, you can format a string without printing by using the `fmt.Sprintf()` function, which returns a formatted string instead of printing it to the console.

Example:
```go
package main

import (
    "fmt"
)

func main() {
    formattedString := fmt.Sprintf("Hello, %s!", "world")
    fmt.Println(formattedString) // Output: Hello, world!
}
```

### 33. What is Type Assertion in Go?
Checking and converting interface types/Type assertion in GoLang is used to extract the underlying value of the interface{} type and check its type.

Example:
```go
var val interface{} = 42
num, ok := val.(int)
```

### 34. What is the use of Type Assertion in Golang?
Type assertion in GoLang is used to safely extract the underlying value and check its type to prevent runtime errors.

### 35. Does Golang support automatic or implicit Type Casting or Type Conversion?
No, GoLang does not support automatic or implicit type casting. Type conversions must be explicit and handled by the programmer.

### 36. How to check the variable type at runtime in Golang?
You can use the `reflect` package in GoLang to check the variable type at runtime.

Example:
```go
// FIRST
	fmt.Printf("var1 = %T\n", var1)
	
	// SECOND
	fmt.Println("var1 = ", reflect.TypeOf(var1))
	
	// THIRD
	fmt.Println("var1 = ", reflect.ValueOf(var1).Kind())
	
```

### 37. How to compare two structs in Golang?
In GoLang, you can compare two structs by comparing their individual fields using the `==` operator or by using the reflect.DeepEqual() function from the `reflect` package.

Example:
```go
package main

import (
    "fmt"
    "reflect"
)

type Person struct {
    Name string
    Age  int
}

func main() {
    person1 := Person{"Alice", 30}
    person2 := Person{"Alice", 30}
    fmt.Println(person1 == person2) // Output: true

    fmt.Println(reflect.DeepEqual(person1, person2)) // Output: true
}
```

### 38. How to compare two maps in Golang?
In GoLang, you can compare two maps by iterating over their keys and values and comparing them manually, or you can use the reflect.DeepEqual() function from the `reflect` package.

Example:
```go
package main

import (
    "fmt"
    "reflect"
)

func main() {
    map1 := map[string]int{"a": 1, "b": 2}
    map2 := map[string]int{"a": 1, "b": 2}
    fmt.Println(reflect.DeepEqual(map1, map2)) // Output: true
}
```
### 39. Can we have exceptions in Golang?
No, GoLang does not have traditional exceptions like other programming languages. Instead, it uses error handling through return values, the `error` interface, and the `panic` and `recover` mechanism.

### 40. What is defer and panic in Golang?
- `defer`: Defer in GoLang is a statement that schedules a function call to be run after the function completes, but before it returns.
- `panic`: Panic in GoLang is a built-in function that stops the ordinary flow of control and begins panicking.

### 41. Explain pointers in Go?
Pointers in GoLang are variables that store the memory address of another variable. They are used to indirectly refer to a value rather than holding the value itself.

Example:
```go
package main

import "fmt"

func main() {
    var x int = 42
    var ptr *int = &x
    fmt.Println(*ptr) // Output: 42
}
```

### 42. What are Goroutines?
Goroutines in GoLang are lightweight threads managed by the Go runtime. They enable concurrent execution of functions and are more efficient than traditional threads.

### 43. What are anonymous Go Routines?
Anonymous goroutines in GoLang are goroutines launched without giving them a name. They are often used for concurrent execution of functions without having to explicitly define and name them.

Example:
```go
go func() {
    // Your concurrent code here
}()
```

### 44. What are waitgroups in Go?
WaitGroups in GoLang are used to wait for a collection of goroutines to finish executing before proceeding. They synchronize the execution of multiple goroutines.

### 45. What is a receive operator in Go?
The receive operator `<-` in GoLang is used to receive data from a channel. It blocks until data is available to be received.

### 46. What are channels in Go?
Channels in GoLang are a type that provide a way for goroutines to communicate with each other and synchronize their execution.

### 47. What is a unidirectional channel in Go?
A unidirectional channel in GoLang restricts the direction in which data can flow. It can be either a send-only or a receive-only channel.

### 48. How to declare a channel as a ValueType or Reference Type separately?
Channels in GoLang are reference types by default. To create a channel of a specific value type, you specify the type when declaring the channel.

Example:
```go
ch := make(chan int) // Channel of int type
```

### 49. Should we use goroutines in a program with Global variables?
Yes, you can use goroutines in programs with global variables. However, you should ensure proper synchronization to avoid data races and unexpected behavior.

### 50. Access Modifiers in Go?
In GoLang, identifiers that start with a capital letter are exported from the package and accessible from other packages. Identifiers that start with a lowercase letter are unexported and accessible only within the same package.

### 51. Can we access an unexported variable of a package in another package in Go?
No, unexported variables of a package cannot be accessed from another package in GoLang. They are accessible only within the same package.

