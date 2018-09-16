### Option One: CrystalsCollector Game (Recommended)

![Crystal Collector](Images/1-CrystalCollector.jpg)

1. [Watch the demo](https://youtu.be/yNI0l2FMeCk).

2. The player will have to guess the answer, just like in Word Guess. This time, though, the player will guess with numbers instead of letters. 

3. Here's how the app works:

   * There will be four crystals displayed as buttons on the page.

   * The player will be shown a random number at the start of the game.

   * When the player clicks on a crystal, it will add a specific amount of points to the player's total score. 

     * Your game will hide this amount until the player clicks a crystal.
     * When they do click one, update the player's score counter.

   * The player wins if their total score matches the random number from the beginning of the game.

   * The player loses if their score goes above the random number.

   * The game restarts whenever the player wins or loses.

     * When the game begins again, the player should see a new random number. Also, all the crystals will have four new hidden values. Of course, the user's score (and score counter) will reset to zero.

   * The app should show the number of games the player wins and loses. To that end, do not refresh the page as a means to restart the game.

   ##### Option 1 Game design notes

* The random number shown at the start of the game should be between 19 - 120.

* Each crystal should have a random hidden value between 1 - 12.

-----

Pseudo-code/Steps:

1. Wireframe on paper, what I would like this game to look like based on the specifications that have been presented to me.

2. Create the basic HTML structure so that I can begin to mainpulate the DOM through the use of jQuery.

3. (Make a personal effort to really keep your code organized!)

4. Think about what variables I'm going to need for this game. Write them down.

5. Think about different functions and how they might be arranged. Write those down.

6. Psuedo-code the structure for the game-code.

7. Write the code.

8. test/debug/test/debug.

9. Once game is at it's most basic finish status, read and consider to implement any bonus material either stated within the instructions or otherwise.

10. Finalize project.

11. Push to repo and deploy GitHub Pages.
