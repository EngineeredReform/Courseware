# Programming From Scratch

## Outline

- [What is programming?][what-is-programming]
- [What tools do I need?][what-tools-do-i-need]
  - [Physical Tools][physical-tools]
  - [Virtual Tools][virtual-tools]
  - [Mental Tools][mental-tools]
- [Let's Get Started][lets-get-started]
  - [What is Data?][what-is-data]
    - [Data Types][data-types]
      - [Boolean][boolean]
      - [Character][character]
      - [Float][float]
      - [Integer][integer]
      - [String][string]
    - [Data Structures][data-structures]
      - [Array][array]
      - [Dictionary][dictionary]
    - [Flow Control][flow-control]
      - [For Loops][for-loops]
      - [While Loops][while-loops]
      - [If Statements][if-statements]
      - [Switch Case Statements][switch-case-statements]

## What is Programming?

To understand what programming is, first we need to understand a computer. Computers have lots of whizzing and whirring parts, sure, but we don't need to get that deep. Think of a computer like a car - we don't need to understand all of the underlying mechanics to use it to help us perform tasks. Same goes for a computer.

So what do we need to know? We need to know that a computer is a series of inputs and outputs. The keyboard and mouse, for instance, are inputs (and sometimes outputs). The screen or monitor is our main output but we also have speakers and some keyboards have lights under the keys and small screens too. Inputs take data from the user and give it to the computer. Outputs take data from the computer and give it to the user. That's it.

Programming (sometimes called "coding" or "development") is nothing more than giving a computer a set of instructions to follow each time a user runs your program. A very simple example of this is a calculator. When you use the input (the keypad) and type "1+1=" you see a "2" appear on the screen. This is you giving this little computer a set of instructions for it to run, so you're already a programmer! What would happen if you typed "+11=" into the calculator? What if you typed in "1=1+" into the calculator? You wouldn't get "2" because you input the instructions incorrectly and the calculator doesn't know what to do with that. This isn't quite how programming works these days, we have a ton of tools that help us to not write the instructions incorrectly, which we'll talk about next in the [What Tools do I Need][what-tools-do-i-need] section.

## What Tools do I Need?

### Physical Tools

You need a computer - almost any computer will do. We're going to eventually write enterprise applications, but even then most computers will suit your needs here. Laptops these days are powerful enough to handle the task.

### Virtual Tools

You'll need an IDE also known as an Integrated Development Environment - a fancy way of saying "programming software." Microsoft makes a great piece of software called [Visual Studio Code][vscode] (VSCode for short), which has plugins that allow you to work with various languages. We'll talk more about languages later.

### Mental Tools

You need nothing more than your brain and some general logic, which can be learned pretty easily. Several books and websites on the topic exist and will show you things like:

```text
Statement:  If A is true, then B is false.
Scenario:   A is true.
Result:     B must be false.
```

## Let's Get Started

### What is Data?

Simple answer: almost everything is data. Usernames, passwords, amount of money in your bank account, names of highways in the US, the current time, directions to the nearest McDonalds - it's all data, but it's all different _types_ of data. Now you might be thinking "what types of data are there?" Don't worry, we're about to get into that!

#### Data Types

##### Boolean

- Also known as: __*bool*__
- It is an extremely simple data type as it only has two possible values: _true_ or _false_.
- Sometimes represented by _0_ or _1_.

##### Character

- Also known as: __*char*__
- It can only hold a single [alphanumeric](https://www.merriam-webster.com/dictionary/alphanumeric) character.
- Examples: `'c'` or `'&'` or `'5'`

##### Float

- Also known as: __*real*__
- It is responsible for holding fractional numbers - anything with a decimal.
- Examples: `36.02` or `1.00`

##### Integer

- Also known as: __*int*__
- It can only hold a single whole number.
- Examples: `1` or `982`

##### String

- Also known as: __*str*__
- It is a _list of characters_ and most languages allow you to access it as such.
- Technically not a real data type as it is an array (data structure) populated with character (data type) elements
- Examples: `"Hello"` or `"My name is RJ."`

#### Data Structures

##### Array

- Also known as: __*list*__
- An array typically contains a number of items (elements) of the same [data type][data-types]. Think of a list of groceries as an example - it's all the same type (grocery items) and you can add to it, remove from it, or look for a particular item.
- You can access an element in an array using its _index_ - the first element in an array is typically index 0. If I had an array of foods like `[ "corn", "eggplant", "turkey" ]` and I wanted to get the element at _index 0_, it would be `"corn"` where the element at _index 2_ would be `"turkey"`.
- Examples: `[ 1,2,3,4,10 ]` or `[ 'h','e','l','l','o' ]`

##### Dictionary

- Also known as: __*map*__
- A dictionary contains key-value pairs that look like this: `key: value` where all of the keys must be unique, just like in a real dictionary. A word (key) in a dictionary may have multiple definitions (values), but there's only one place to look up any particular word. For instance, you wouldn't expect to find the definition for the word _Aardvark_ in 10 different locations in the dictionary.
- The keys have to be unique as this is what you use to look up the values in the dictionary, just like a real dictionary, except in this case, the order does not matter.
- Examples: `{ name: "RJ", numberOfCars: 1, numberOfKids: 3.0, favoriteFoods: [ "spaghetti", "eggplant" ] }` or `{ aardvark: "an animal", potato: "a food", rice: "a food" }`

### Flow Control

Now that we have data types and data structures we need to do stuff with our data. For instance, what if we want to search for a specific element in an array but we don't know the index? That's where we get into flow control! There are multiple types of flow control, each with their own list of pros and cons.

- For loops
- While loops
- If statements
- Switch-case statements

#### For Loops

Typically used with a counter, for loops are typically used to iterate over a known number of elements. For example, if my friend gives me a list of their favorite cars and I want to see if my favorite car is also in their list, I could loop over the list and check each element, just as I would do with a list written on paper.

```text
friendsFavoriteCars = [ "1964 Lincoln Continental", "1974 Ford Bronco", "1966 Ford Mustang" ]
myFavoriteCar = "1966 Ford Mustang"

for each car in friendsFavoriteCars
  get the current car in the list
  compare it with myFavoriteCar
  print some data back to the user so we can solve the problem
```

Looking at this [pseudo-code](https://en.wikipedia.org/wiki/Pseudocode) we can see exactly what we need to do.

#### While Loops

TODO: finish this

#### If Statements

TODO: finish this

#### Switch-Case Statements

TODO: finish this

## Appendix

<!-- INTERNAL LINKS -->
[what-is-programming]: #what-is-programming
[what-tools-do-i-need]: #what-tools-do-i-need
[physical-tools]: #physical-tools
[virtual-tools]: #virtual-tools
[mental-tools]: #mental-tools
[lets-get-started]: #lets-get-started
[what-is-data]: #what-is-data
[data-types]: #data-types
[boolean]: #boolean
[character]: #character
[float]: #float
[integer]: #integer
[string]: #string
[data-structures]: #data-structures
[array]: #array
[dictionary]: #dictionary
[flow-control]: #flow-control
[for-loops]: #for-loops
[while-loops]: #while-loops
[if-statements]: #if-statements
[switch-case-statements]: #switch-case-statements

[appendix]: #appendix

<!-- EXTERNAL LINKS -->
[vscode]: https://code.visualstudio.com/
