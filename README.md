# Flapy Birds A.I.
A flappy bird game that learns to play by itself using Deep Q Learning and JavaScript and exciting technologies such as Tensorflow.js, D3 and Webpack.

<p align="center">
  <img src="demo.gif" width="820" alt="Demo of DQN AI Flappy Bird" />
</p>

### Live demo
You can click [here](https://danielpaz6.github.io/Flappy-Birds-DQN/) for live demo.

### Overview
This project follows the description of the Deep Q Learning algorithm described in [Playing Atari with Deep Reinforcement Learning](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf) and shows that this learning algorithm can be further generalized to the notorious Flappy Bird.

Moreover, in order to optimize it even more, I used DDQN architecture.

### Installing
Clone and install dependecies

```
git clone https://github.com/danielpaz6/Flappy-Birds-DQN.git
cd Flappy-Birds-DQN
npm install
npx webpack
```

### Disclaimer and further more information
- The canvas game made by [sakri](https://codepen.io/sakri/pen/gGahJ)
- Great article about DQN in Python: [Link](https://keon.github.io/deep-q-learning/)
- Great example with DQN and DDQN in Python: [Link](https://github.com/ritakurban/Practical-Data-Science/blob/master/DQL_CartPole.ipynb)