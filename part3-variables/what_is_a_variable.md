# What is a Variable?

A **variable** is a label that refers to a value stored in memory. Let’s explore
what that entails:

```ruby
x = 5
```

As with algebraic variables, the name of the variable is on the left side of `=`,
and its value is on the right. `=` is the **assignment operator**. Here it
_assigns_ the variable `x` to the value `5`. When one first assigns a variable
to a value, one also _defines_ that variable. A defined variable has meaning in
the program, e.g., `x` means `5`.

By assigning a variable to `5`, we indicate to the Ruby interpreter that the
integer `5` is worth storing in memory. The variable `x` points to the location
of `5` in memory, allowing one to retrieve and manipulate that value. The
variable "stands in" for the value, giving the programmer a convenient handle on
it.

```ruby
x + 2
=> 7
puts x
5
=> nil
```

Any object can be assigned to a variable. Variables can also be reassigned. Run
each of the following lines in the Repl.it shell.

```ruby
a = true
b = "dog"
b = a
a = 7.5
```

Predict the new values of `a` and `b`. Type `a` in the shell and press enter. Do
the same for `b`.

```ruby
a
=> 7.5
b
=> true
```

When `b` is reassigned to `a`, `a` refers to `true`. The value of `b` therefore
also becomes `true`. The later reassignment of `a` to `7.5` does not affect the
value of `b`.