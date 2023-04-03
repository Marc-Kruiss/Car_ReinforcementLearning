# Car_ReinforcementLearning
This project is a 2D space game that simulates an automated car using pure HTML, CSS, and JavaScript with no extra libraries. The model is trained using reinforcement learning and trains with 400 cars in parallel.

## Usage
To use the program, follow these steps:

1. Clone the repository and navigate to the project directory.
`git clone https://github.com/Marc-Kruiss/Car_ReinforcementLearning`

`cd Car_ReinforcementLearning`

2. Open the index.html file in a web browser.

3. The model will automatically learn how to navigate through the space. Save the current best model with the **Save** button or delete the whole knowledge with the other button.

## How it Works
The car is a simple sprite that moves in a 2D space. The objective of the car is to reach the end of the level without colliding with any obstacles. The model is trained using reinforcement learning, which means that it learns by trial and error. It uses a neural network to predict the best action to take in any given situation.

The model trains with 400 cars in parallel to speed up the learning process. The cars are randomly initialized with different weights, and the weights are updated based on the reward they receive at the end of each level. The reward is based on how far the car gets and whether it collides with any obstacles.

The training process can take a while, depending on the complexity of the level and the number of cars used. Once the model is trained, it can be used to play the game automatically.

## References
Reinforcement Learning: https://en.wikipedia.org/wiki/Reinforcement_learning