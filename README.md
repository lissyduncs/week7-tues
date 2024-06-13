# week7-tues
# Psuedocode
- Plain Language description of steps
- Bridge between programs login and the code

## Importance
- Helps to understand the programs logic, so easier to code
- Improves collaborations in team projects
- Helps with troubleshooting
- Identify the core areas of the programming that needs to be done

## Characteristics
- Simple, no syntax. understandable
- Structured. Follow logical sequence
- Abstracted. Focus in logic rather than syntax
- Thorough walkthrough that helps explain the logic

## Basic Constructs
- Sequential
    - step 1- do this
    - step 2- do this

Condiitional
    - If condition then
        do something
    - ELSE
        do something else
    END IF

Loops
    WHILE condition meets
        do something
    END WHILE

    FOR EACH item in collection
        do something
    END FOR

## Practical examples
- EG 1: Calculating sum of a list of numbers
    [1,2,3,4,5]
    Initialise sum to 0
    for each number in the list
     add number to sum
     END FOR
     Print sum

     EG 2: Findimg maximum number in a list
     Initialise max value to first number in a list
        FOR each number in the list
            IF numberis greater than max THEN
                set max to number
            END IF
        END FOR
        print max

## Functions

- One of the best toold for following DRY coding principles
- Blocks of code that performs a specific task, like your phone's features
- can be reused and helps make the program modular

## Syntax

- Defining a function

...
    def function_name(parameters):
    # code blocks
    return value

Calling a function
...
    function_name

## Scope
- Children can assess parents scope
- Children cannot access parents scope

 ## return keyword
 - Returns a value from a function

 ## Arguments and parameters
 - Arguments are values you can pass to the function
 - Parameters arae variables that enable us to pass arguements to our function
 - 
 -Default arguments/ 
- 