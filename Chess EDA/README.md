# Chess Games Exploratory Data Analysis (EDA)

This project provides a comprehensive exploratory data analysis of chess games from Lichess. The dataset contains game details, including the mode, result, termination type, average ratings of the players, and more.

## Goals:

1. Understand the distribution of player ratings.
2. Investigate how games typically end (e.g., checkmate, time forfeit).
3. Explore the relationship between player ratings and game outcomes.
4. Identify popular openings and strategies.

## Steps and Results:

### 1. Data Loading and Preliminary Checks:
The dataset was loaded from a CSV file, and basic checks were performed to understand its structure, missing values, and data types.

### 2. Data Cleaning:
Necessary data cleaning steps were executed to handle missing values and derive new features like the average rating of players and the rating difference between players.

### 3. Data Summary:

#### 3.1 Average Rating Distribution:

The distribution of average ratings of the players for each game is approximately bell-shaped. Most games involve players with mid-range ratings, while fewer games involve very high or very low-rated players.

#### 3.2 Rating Difference Distribution:

The distribution of rating differences between players in each game is centered around zero. Many games feature players with similar ratings, but some games have a significant rating difference.

#### 3.3 Game Mode Distribution:

The most prevalent game mode is Blitz, followed by Bullet. Other modes are less frequent.

#### 3.4 Game Results Distribution:

Games where White wins are most common, followed by games where Black wins. Draws are relatively less frequent.

#### 3.5 Termination Types Distribution:

Most games end in regular checkmates or stalemates. Time forfeits are also common, especially in faster game modes.


### 4. Detailed Visualizations:

Further in-depth visual explorations provided insights into various aspects of the games.

#### 4.1 Most Common Opening Moves:

The bar chart displays the most frequent opening moves. The moves `e4` and `d4` are by far the most popular, which is consistent with common chess knowledge.

#### 4.2 Relation between Average Rating and Termination Type:

The visualization indicates that while higher-rated players generally manage their time better, time forfeits can still occur across all rating levels.

#### 4.3 Relation between Mode and Number of Moves:

The faster-paced games like Bullet tend to have shorter numbers of moves, while slower-paced games like Classical allow for more extended play.

#### 4.4 Correlations between Rating Difference, Average Rating, and Number of Moves:

A heatmap shows the correlations between the selected numerical variables, suggesting that these factors are largely independent of each other.

#### 4.5 Common Sequences of the First Three Moves:

The sequences highlight popular openings like the Ruy-Lopez and Sicilian Defense.
