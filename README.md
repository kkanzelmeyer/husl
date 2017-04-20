# HUSL Player Grading Algorithm

## Contributing
1. Clone the project
2. Open `index.html` in Chrome
3. Load one of the data files in the repo
4. Grab a beer, open the code, make the algorithm better

## The algorithm
The algorithm uses five categories to rank a player - age, height, experience, skill, and activity level. Each of the five categories has a "weight" assigned to it in the total score calculation. A higher weight means the category is more important in determining a player's rank.

Once the score is calculated, it is multiplied by a constant called "competency". A player's competency is determined soley by the player's input in the "height" form fields. The form asked for the players height and gave the user "feet" and "inches". For example, if a player is 5'11", `5` would be entered in the `feet` input and `11` would be entered into the `inches` input. If the player put anything different, the player's competency score is negatively affected.
