#Notes for Snake AI Algorithm

##Part 1: Theory

###Reinforcement Learning
An area of ML concerned with how software agents ought to take actions in an environment in order to maximize the notion of cumulative reward

###Deep Q Learning 
This approach extends reinforcement learning by using a deep neural network to predict the actions

Q Value = Quality of action

Bellman Equation:
NewQ(s,a) = Q(s,a) + learningr[R(s,a) + discountrmaxQ'(s',a')-Q(s,a)]
Q=model.predict(state0)
Qnew=R+discountR*max(Q(state1))
loss=(Qbew-Q)^2 (mean squared error)

##Attribution
Patrick Loeber, YouTube
https://github.com/patrickloeber/python-fun/blame/master/snake-pygame/snake_game.py
