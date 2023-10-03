_Wordfind_ is a simple `javascript` library for generating (hopefully fun) word find (also known as word search) puzzles. Just give it a set of words and a few milliseconds later it will spit out a puzzle containing those words.

The core `wordfind.js` library contains no dependencies and will work both in the browser and in node.js. The repository also includes a fully functional word find game (aptly called `wordfindgame.js`) as an example. The game has a dependency on `jQuery`.

This is a fork of https://github.com/bunkat/wordfind which doesn't get confused with capital words in the word list, and colors each successive found word a different color. For fun, I use a confetti effect when the game is won.

Check out the sample game at http://Lucas-C.github.com/wordfind/.
