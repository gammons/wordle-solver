# Wordle helper

A (very) simple program to help with the wordle game.

### Usage

The program takes 3 arguments:

`wordle <mask> <must_include> <must_exclude>`


* **mask** is the current guess state, including letters that are already known.  For instance, `?O??T` would indicate that the letters `O` and `T` are already green.
* **must_include** is a string of letters that must be included in the word, e.g. they are yellow on the board.  For instance "RT" 
* **must_exclude** is a string of letters that are not in the word.  These are gray letters on the board.

### Example

Suppose the board looks like this:

![image](https://user-images.githubusercontent.com/38560/150330651-ec3449ed-3fc9-4111-9e30-4a8a3018a3c7.png)

Run the wordle program (e.g. `wordle ?O??T R LEANSCU`) and it will spit out 2 guesses:

* vomit
* robot
