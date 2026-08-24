In R, a variable is a name used in source code to reference a storage location in the computer's memory. We can create a variable by writing the name of the variable followed by an assignment operator (`<-`{.r} or `=`{.r}) and then the value we want to store in that variable. If we use the variable name later in our code, R will replace it with the value we assigned to it. In the example below, we create a variable called `age`{.r} and assign it the value `25`{.r}. When we place a variable in the parentheses on a call to the `print`{.r} function the value of variable is returned. Here, printing the value of `age`{.r}, outputs `[1] 25`{.r}.

```r-cell
age &lt;- 25
print(age)
```

# Variable Naming Rules

When naming variables in R, there are a few important rules to follow:

* Variable names can only contain letters (a-z, A-Z), numbers (0-9), and underscores (_) or periods (.).
* Variable names cannot start with a number. For example, `1st_place`{.r} is not a valid variable name.
* Variable names cannot start with a period followed by a number. For example, `.1st_place`{.r} is not a valid variable name.
* Variable names are case-sensitive. This means that `age`{.r}, `Age`{.r}, and `AGE`{.r} are considered different variables.
* Variable names cannot contain spaces or special characters (except underscores and periods).

In addition, variables should not use R reserved words (keywords), as these have special meanings in the language. These include:

* `if`{.r}
* `else`{.r}
* `for`{.r}
* `while`{.r}
* `repeat`{.r}
* `break`{.r}
* `next`{.r}
* `function`{.r}
* `return`{.r}
* `in`{.r}
* `TRUE`{.r}
* `FALSE`{.r}
* `NULL`{.r}
* `Inf`{.r}

# Variables and Expressions

If the code on the right-hand side of the assignment operator is an expression, R will first evaluate the expression and then assign the resulting value to the variable. For example, in the code below, we create a variable called `x`{.r} and assign it the result of the expression `5 + 3`{.r}. R evaluates the expression to get `8`{.r}, and then assigns that value to `x`{.r}. When we print the value of `x`{.r}, R outputs `[1] 8`.

```r-cell
x &lt;- 5 + 3
print(x)
```

# Changing Variable Values

We can change the value of a variable by assigning a new value to it. For example, in the code below, we first create a variable called `count`{.r} and assign it the value `10`{.r}. We then change the value of `count` to `20`{.r} by assigning a new value to it. When we print the value of `count`{.r}, R outputs `[1] 20`.

```r-cell
count &lt;- 10
count &lt;- 20
print(count)
```
