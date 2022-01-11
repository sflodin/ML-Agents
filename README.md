# ML-Agents
Personal machine learning project to simulate various environments and build up more and more complex agent AI's
First I simply followed some tutorials on YouTube to familiarize myself with the Ml-Agents/Unity Environment

# Pushing Two Buttons
Goal: Get an Agent to push two buttons
Rewards:
  - Reaching both buttons
  - Exponentially higher reward for reaching the goal quickly

Failures: 
  - Hitting walls
  - Running out of time (6000 steps)

Mistakes/What I learnt:
  - I tried having two seperate rewards one for the first button and a larger one for the second. This disinsentivized the AI to keep searching for a second button as it was content with its small reward. This was solved by only having the final reward.
  - Had difficulties understanding how observation size worked. 


