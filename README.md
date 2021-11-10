# Deep Q-Networks(DQN)
This repo contains a very simple implementation of an agent playing LunarLander in the <a href='https://github.com/openai/gym'>OpenAI-Gym</a> environment, the training has been accomplished by using the <a href='https://arxiv.org/abs/1312.5602'>DQN</a> method of Deep Reinforcement Learning and TensorFlow(CPU).

https://user-images.githubusercontent.com/10044095/124774963-82c75500-df3e-11eb-94d5-9a1ebc8af6d4.mp4 

## Tensorboard
To inspect in-real-time logs, run the code below in the project directory to start <a href='https://www.tensorflow.org/tensorboard'>tensorboard</a>:
```
tensorboard --logdir "log/"
```
then, connect to its interface which, by default, should be *https://localhost:6006*

# Dependencies
* Python(3.8.8)
* Numpy(1.19.3)
* TensorFlow(2.6.0)
* Matplotlib(3.4.2)
* Gym(0.18.3)

# Results
![1](https://i.imgur.com/dcaq8or.jpg)

