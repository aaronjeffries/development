# Tennis coding test.

Tennis has a rather quirky scoring system, and to newcomers it can be a little difficult to keep track of. The tennis society has contracted you to build a scoreboard to display the current score during tennis games. 

Your task is to write a “TennisGameImpl” class containing the logic which outputs the correct score as a string for display on the scoreboard. When a player scores a point, it triggers a method to be called on your class letting you know who scored the point. Later, you will get a call “score()” from the scoreboard asking what it should display. This method should return a string with the current score.

The rules of tennis scoring can be summarized below:

1. A game is won by the first player to have won at least four points in total and at least two points more than the opponent.
2. The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "Love", "Fifteen", "Thirty", and "Forty" respectively.
3. If at least three points have been scored by each player, and the scores are equal, the score is "Deuce".
4. If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "Advantage" for the player in the lead.

# How to completing the "test"

1. When all the tests pass you are done.
2. Don't change the TennisTest class.  You can change anything under the src/main/java source folder. 
3. You may use the [Javadocs](https://docs.oracle.com/javase/8/docs/api/) for reference.
4. This test is to see your thought process.  You don't necessarily need to finish to "pass".  If you get stuck you're welcome to ask questions. 
5. You need only report the score for the current game. Sets and Matches are out of scope.