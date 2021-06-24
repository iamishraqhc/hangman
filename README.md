Hangman app in React. In this project, I have taken some help from the vanilla hangman project of Brad Traversy and the tutorial from CodeSTACKr. Then I tweaked some of the things, added some more words and so on.

The code works like there are a set of words stored in a list. The words are randomly chosen for being guessed. 

When you start guessing, if you answer correctly, the letter will be placed in the blank. And if you answer wrongly, the hanging man will start developing. The wrong letter will also be displayed on the screen.

If you choose a letter that was selected before, then you will get a notification saying that this was used before. 

And finally, after the game ends, win or lose, you will be asked if you want to play the game again. So if you press ok, then everything will be refreshed and a new random word from the list will be generated for you to guess.

The site is live here: https://hangman-game-in-react.netlify.app/