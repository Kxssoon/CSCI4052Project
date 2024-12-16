# Checkpoint 4- NLP
## Nicholas Kissoon - 100742790

### Introduction

This is for the NLP portion of the project. I have implemented a chatbot that is able to take queries and answer them to the best of their ability. It is in it's early testing however the ambition here is to get it to respond to not only user queries but based off what the commentator is saying live. GPT2 was used in order to achieve this. Taking any recommendations you have for this model. It is a simple model right now that is handling question/answer sessions under certain conditions, such as a resticted input length. The aim is to make some of these restrictions less intrusive, to truly allow both the user and commentators to effortlessly communicate and ask away their questions, while getting efficient and meaningful advice or help.

### Results

#### Input
How many people are on a basket ball team?

#### Output
It's hard to say. The average player is averaging around 20 points per game. So if you look at the NBA, it's very different. You're going to have a bunch of guys that are playing a lot more minutes, but it's a different league.

So when you look at the average NBA team, it's not that you're going to have a lot of players who are on a basket ball team, but

#### Takeaways

As you can see here there is still quite some work to do, however in fairness it did bring up a valid point that I more often that not overlook. That is, the NBA is not the only professional league and so the answer to this question isn't as straightforward as one may think. However, I plan on aiming to add a filter or a keyword for NBA in an attempt to keep things on track and relevant.

### Reinforcement Learning

- Environment could be the game itself (things like the player position, ball posession, score and the time remaining)
- Then actions like passing, shooting and blocking just to name a few can be included
- The reward would be given based upon the correct prediction
- The agent would take the game as an input and output a probability distribution of the possible actions.