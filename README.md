# Predicting-MLB-Games-with-Machine-Learning
Combine classification algorithms to predict the winner of each game

Kyle Johnson

### Project Motivation
Being able to predict the future, even just slightly better than a coin flip, can be enourmously lucrative.  Without having a crystal ball, the next best thing that we can do is harness the power of large datasets to find hidden patterns that can be used to give a slight edge in making large amounts of predictions. Baseball is perfectly suited for this because virtually everything that happens is quantifiable and repeats hundreds of times per game and each game is repeated thousands of times per year. The goal of this project is to use machine learning techniques to make predictions about Major League Basebal games in such a way that is better than the Vegas book makers. Being able to predict 70% of games correct is of no use if Vegas also predicted those same games correctly; in order to have a useful model, I must create one that consistently makes money when betting against Vegas bookmakers.

Please see the notebook titled "Summary_Start_Here" for a detailed road map through this project in order fully understand the process.

### Process Overview
The data for this project was sourced from MLB Advanced Media's API, baseball-reference.com and sportsbookreviewonline.com and then pre-processed into a useful form.  Four classification models were then created and optimized, which then used a voting procedure to make a final prediction.
![Diagram](https://github.com/kylejohnson363/Predicting-MLB-Games-with-Machine-Learning/blob/master/MLB%20Diagram.JPG)

### Benchmark to Outperform
The performance benchmark for this project is the predictions that the Vegas odds-makers create.  If the created model can make money by betting against Vegas, then we know the model has added value.  Below is a graph showing the relationship between the confidence that Vegas has in a prediction vs the percentage of time that prediction is correct.  The orange and blue lines are quite coorelated, meaning that Vegas is quite good at predicting games, which  makes sense because they would be out of business very quickly otherwise.

# Conclusions:
-I was able to create a model that predicts MLB games more accurately and more profitably than the Vegas odds in a statistically significant way. I did this by querying data from several online baseball databases and then optimizing several different classification models, before combining them to vote on the outcome of each game.

-Oddly enough, it seems that always betting with the Vegas odds is a profitable strategy but using the model created in this project is potentially almose twice as profitable.
# Future Work:
For further exploration, I would use more types of data (new and highly advanced statistics) and more games from previous seasons. I would also automate the process of gathering the necessary data for today's games and publishing a report of which games to bet on.
