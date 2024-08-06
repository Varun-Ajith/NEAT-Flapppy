# NEAT-Flapppy

This project uses the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train an AI to play Flappy Bird. The AI learns to control the bird and avoid pipes by evolving over generations.

![Flappy Bird AI](flappy.gif)

## Overview

This project demonstrates the use of the NEAT algorithm to train a neural network to play Flappy Bird. The AI controls the bird, attempting to pass through as many pipes as possible without collision. Over time, the AI improves its performance through evolutionary techniques.

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Varun-Ajith/NEAT-Flapppy.git
   cd NEAT-Flapppy
   ```
2.**Install required packages:**
Ensure you have Python installed, then install the necessary packages using pip:
`pip install pygame neat-python`

## Files
1. `flappy_bitd.py`: The main Python script that runs the Flappy Bird game and NEAT training.

2. `config-feedforward.txt`: Configuration file for the NEAT algorithm.

3. `flappy.gif`: GIF demonstrating the AI playing Flappy Bird.

## How to run
1. Ensure you are in the project directory:
   `cd NEAT-Flapppy`
2. Run the game:
   `python flappy_bitd.py`

## Project Structure
1. **Bird Class**: Represents the bird and its movements.
2. **Pipe Class**: Represents the pipes and their positions.
3. **Base Class**: Represents the ground that moves to simulate the bird flying.
4. **Main Function**: Handles the game loop, NEAT algorithm integration, and rendering.
   
## NEAT Algorithm
The NEAT algorithm is a genetic algorithm that evolves neural networks. It adjusts the weights, biases, and structures of the networks over generations to optimize performance.

## Configuration
The config-feedforward.txt file contains the configuration for the NEAT algorithm. Key parameters include population size, fitness criteria, mutation rates, and network structure.

## Contributing
Feel free to fork this repository and submit pull requests. Any enhancements, bug fixes, or general improvements are welcome.

## License
This project is licensed under the [MIT License](LICENSE).
