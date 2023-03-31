# Implementation_Of_RL_Algorithms
## Gym-minigrid Implementation
Training an agent using RL tabular methods, namely TD learning on gym-minigrid

gym-minigrid - https://github.com/maximecb/gym-minigrid

The agent has been trained using 3 algoriths:

Sarsa0
Sarsa Lambda
Q-Learning
The agent was trained on 4 environments:

5x5 Empty room
6x6 Empty room
8x8 Empty room
Four Rooms
## Resuts:
Graphs between episode and rewards and episode and steps were plotted.

## Sarsa0:

#### 5x5 Empty room
![image](https://user-images.githubusercontent.com/102024497/229156002-c9e1a276-8736-44c6-a0f2-f86365b0c7d0.png)

#### 6x6 Empty room
![image](https://user-images.githubusercontent.com/102024497/229156430-f2ca996c-6134-4964-8912-48fba7a02df8.png)

#### 8x8 Empty room
![image](https://user-images.githubusercontent.com/102024497/229156467-1efb1a00-ac7e-49aa-a5c1-8a1f2f03b774.png)

## Sarsa-lambda
#### 5x5 Empty room
![image](https://user-images.githubusercontent.com/102024497/229156925-a313c76d-169b-4ad5-a91c-c3263b1911f5.png)

#### 6x6 Empty room
![image](https://user-images.githubusercontent.com/102024497/229156987-48575ef2-7de3-4a74-bf5c-8f789deb9ca3.png)

#### 8x8 Empty room
![image](https://user-images.githubusercontent.com/102024497/229157043-6f9a9019-e3ca-449f-ae66-1cde5bb1ae34.png)

## Four Rooms
#### For alpha = 0.1
![image](https://user-images.githubusercontent.com/102024497/229157102-f2fc23be-6dd9-418c-a102-878c5708b7d7.png)

#### Comparing different alpha:
![image](https://user-images.githubusercontent.com/102024497/229157179-577296c8-5429-4b7e-ab91-72c112d561e3.png)

## Q-Learning:
#### 5x5 Empty room
![image](https://user-images.githubusercontent.com/102024497/229157317-835aabbf-85b9-4514-8e2f-95f2fa180018.png)

#### 6x6 Empty room
![image](https://user-images.githubusercontent.com/102024497/229157372-435bde34-ee70-4dbf-95b4-da48c2bc9668.png)

##### 8x8 Empty room
![image](https://user-images.githubusercontent.com/102024497/229157434-88d5b5fa-f309-4210-8d62-f7d748d993f8.png)


## Frozen Lake

The agent controls the movement of a character in a grid world. Some tiles of the grid are walkable, and others lead to the agent falling into the water. Additionally, the movement direction of the agent is uncertain and only partially depends on the chosen direction. The agent is rewarded for finding a walkable path to a goal tile.

![image](https://user-images.githubusercontent.com/102024497/229158867-e4a7485e-be5c-4378-be57-3c9cf3aac393.png)

#### GYM
Gym is a toolkit for developing and comparing reinforcement learning algorithms. It makes no assumptions about the structure of your agent, and is compatible with any numerical computation library, such as TensorFlow or Theano.

The gym library is a collection of test problems — environments — that you can use to work out your reinforcement learning algorithms. These environments have a shared interface, allowing you to write general algorithms.
