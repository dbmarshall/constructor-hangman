# Constructor Hangman

Week Six Homework Part 1: [Advanced Javascript Constructor Assignment](http://ucb.bootcampcontent.com/UCB-Coding-Bootcamp/09-11-2017-UCB-Class-Repository-FSF-FT/blob/master/06-week/homework/part-1/HomeworkInstructions.md).

## Installation

```
git clone https://github.com/dbmarshall/constructor-hangman.git
cd constructor-hangman
npm install
```

## Available Node Commands

* `node game.js`

## Little Extras

* Letter validation built in.  Won't accept integers or multi-character strings. 
* Capitalization of user inputted letter doesn't effect comparisons or display.
* Choice to play more offered to user, rather than auto game restart as in demo GIF.

## Shortcomings

* No prototypes used, as per assignment requirements, although updateDisplayString() sort of acts like a prototype, I think.  Tried to call a simply word.js prototype from game.js but couldn't figure out how to do it.  It would have run if user chooses not to play any more but then did choose to see the full list of artist names. Instead, I console.log the entire array there. 
* Doesn't check for repeated user entries (yet?).  My original hangman game did give users an error if they repeated letter guesses. 

## Author

* **David Morse** ([dbmarshall.github.io](https://dbmarshall.github.io))

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

