# THE EFFECT OF SENTIMENTS IN COMMUNICATION ON A TEAM PERFORMANCE
## by Abay Jumabayev
> Submitted to Central European University <br>
> Department of Economics and Business <br>
> In partial fulfillment of the requirements for the degree of Masters of Arts in Economics

### Abstract
There is a lot of literature exploring the determinants of team performance. Knowing how to improve performance could help in any field where people work in teams. I test how the sentiments in communication, for example, being rude or disrespectful towards the other person, affect the performance of a team. 

A team is a small group of four to six people that (i) are educated and highly paid, (ii) work together for a short period (like projects), and (iii) tend to work remotely. Especially for teams where the line-up changes frequently, it is beneficial to know the effect of toxicity in communication on teamwork because sentiments affect the mood of teammates and the mood affects the performance. As it is difficult to quantify the performance and communication between team participants, such as management consultants, I use Dota 2, an online game, to examine how being toxic affects the performance of a team. Apart from fitting the definition of a team, a team from Dota 2 has measurable performance, win or lose, and a chat log from which the derivation of sentiments is possible. With a dataset of 50,000 Dota 2 matches from an open-source platform, I first calculate whether the message sent was toxic. Then, I apply linear regression to predict the outcome of a match via toxicity and controls, such as game and player attributes. 

I found an economically and statistically significant negative link between a toxic team and its performance. 

**Keywords**: sentiments, toxicity, communication, Natural Language Processing, performance, teamwork, linear regression.


This folder provides:
- [a Thesis in pdf format](https://github.com/JustJAG/the-effect-of-toxicity-on-a-team-performance/blob/d5a8adc694a0884b7c9a566e19cc17c74f17a5a9/Thesis%20The%20effect%20of%20sentiments%20in%20communication%20on%20a%20team%20performance.pdf)
- [data of 50,000 Dota 2 matches](https://github.com/JustJAG/the-effect-of-toxicity-on-a-team-performance/tree/main/Data/Original)
- [data of ~160,000 Wikipedia comments](https://github.com/JustJAG/the-effect-of-toxicity-on-a-team-performance/blob/d5a8adc694a0884b7c9a566e19cc17c74f17a5a9/Code/toxic_classifier/train.csv)
- [a code that creates a model that predicts toxicity of a text](https://github.com/JustJAG/the-effect-of-toxicity-on-a-team-performance/blob/d5a8adc694a0884b7c9a566e19cc17c74f17a5a9/Code/toxic_classifier/toxic_classifier.ipynb)
- [code that runs analysis on Dota 2 matches](https://github.com/JustJAG/the-effect-of-toxicity-on-a-team-performance/blob/d5a8adc694a0884b7c9a566e19cc17c74f17a5a9/Code/Code.ipynb)
