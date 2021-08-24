# Instrcutions

## Create a class `Greeting`
In the file 'Greeting.java' create the `Greeting` class. The class must have the required methods defined below.

### Write an appropriate constructor
The greeting class will need to store one name of a person for a greeting. Setters and/or getters may be needed.

### Write the method `hello`
- @param String name
- @return "Hello there " plus the name of the person being greeted

The method returns a string with the name passed starting with the phrase 'Hello there '

### Write the method `goodbye`
- @return  "Sorry to see you go " + name

The method should return a string with name with the phrase 'Sorry to see you go ' .

### Write the static method `randomHello`
- @param ArrayList<String> words
- @return A random word from the ArrayList

## In the `Main` class:
### Write the method `main`
In the main method:

1. Read in a users name
0. Instantiate a Greeting object for that user
0. Print he user's name with a call to `hello`
0. Read in two users names
0. Change the name of the existing Greeting object
0. Instantiate one new 'Greeting' objects for the new user
0. Print the two users names with a call to `hello` for one user and `goodbye` for the other
0. Read in a random amount of words, stopping when the user enters 'quit'
0. Print a random word from the previous words entered using the `randomHello` method
