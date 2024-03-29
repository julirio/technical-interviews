# Tennis

Your task is to write a “TennisGame” class containing the logic which outputs the correct score as a string. When a player scores a point, it triggers a method to be called on your class letting you know who scored the point. Later, you will get a call “getScore()” from the scoreboard asking what it should display. This method should return a string with the current score.

You can read more about Tennis scores here which is summarized below:

* A game is won by the first player to have won at least four points in total and at least two points more than the opponent.

* The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "Love", "Fifteen", "Thirty", and "Forty" respectively.

* If at least three points have been scored by each player, and the scores are equal, the score is "Deuce".

* If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "Advantage" for the player in the lead.

* You need only report the score for the current game. Sets and Matches are out of scope.

## Scope

Complete `TennisGame.java` to model the given problem. The objective is to create a simple, cohesive OOP model that is able to pass all the tests defined in `TennisTest.java`.
