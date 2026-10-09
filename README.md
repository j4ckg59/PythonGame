OVERVIEW 
This is a number guessing game where the player must guess a randomly generated number between 1 and 100 within five attempts. More points are awarded for guessing the number in fewer attempts. Points are also awarded based on how close the player's closest guess was to the correct number.

After each valid guess, feedback is provided to indicate whether the guess was too high or too low.

FEATURES 
Random number generation
Input validation
Limited attempts
Scoring system
Updatable leaderboard
Score tracking
Replay option
Session statistics

HOW TO RUN 
Clone or download the repository.
Open the Jupyter Notebook containing the game.
Run the notebook cells in order and follow the prompts.

SCORING 
The scoring system is based on two factors: the number of guesses used and how close the player's closest guess was to the secret number.

The number of attempts determines a score multiplier, with fewer attempts resulting in a higher multiplier. Points are then awarded based on the closest guess.

The final score is calculated by multiplying the points awarded for closeness by the multiplier for the number of attempts.

LEADERBOARD 
The leaderboard ranks players according to their scores. Scores are saved in the leaderboard.txt file, allowing the leaderboard to persist between sessions.

If a player uses a username that already exists on the leaderboard, their entry is updated only if they achieve a higher score. This ensures that each player retains their personal best score rather than having multiple entries.