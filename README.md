# Python Notes

### Multi-line comments
- You can use triple quotes to start and end multi-line comments as well:
    `"""`
        `the code found below`
        `will print 'Hello, World!' to the console`
    `"""`
    `print('Hello, World!')`

## Variable names
- Use "snake_case" for Python variable neame
    `variable_name = 10`

## Non-type variable names
- You can declare an empty variable with `None`
    `empty = none`

- When no return value is defined, `None` will be returned
`def my_function():`
    `print("My function)`
    `return`

## Multi-variable Declaration
- You can create new variables by creating them on the same line
    `mountain_name, elevation, class = "Mt Beirstadt", 14045, 1`
    This is the same as:
    `sword_name = "Mt Beirstadt"`
    `elevation = 14045`
    `class = 1`

## Multiple Parameters
- Functions can have multiple parameters (inputs)
    `def add_numbers(a, b)`
        `return a + b`

    `result = add_number(4, 4)`
    `print(result)`

## Order of functions
- Functions must be defined before they are used

## Multiple Return values
- You can return more than one value from a function

## Default values for function arguments
- A default value is created by using the assignment (=) operator in the function
    `def get_name(first_name, last_name = "Unknown")`

## Printing vs Returning
- `print()`: A function that prints a value to the console. 
- `return`: A keyword that returns a value from a function (back to the caller of the function). 
