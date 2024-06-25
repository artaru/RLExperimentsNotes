# Reinforcement Learning Projects: Blackjack, Frozen Lake, and TicTacToe

<p align="center">
  <img src="https://github.com/artaru/RLExperimentsNotes/assets/79018762/f6814cfd-7f74-45bd-9dfc-1ac9e0f82793" />
</p>

## Overview

This project explores the application of Reinforcement Learning (RL) and Monte Carlo methods across different environments to develop optimal strategies:

1. **Blackjack**: A card game where the player aims to reach a card sum close to 21 without exceeding it, competing against a dealer.
2. **Frozen Lake**: A grid-world environment where an agent navigates from a starting point "S" to a goal "G" while avoiding holes "H".
3. **TicTacToe**: A deterministic two-player game where the goal is to align three symbols in a row, column, or diagonal.

## Components

### Blackjack Reinforcement Learning

#### Environment:
Simulates rounds of Blackjack with defined rules and rewards based on player actions and outcomes against the dealer.

#### Observations:
The game state is represented by the player's current sum, the visible dealer card, and the presence of a usable ace.

### Frozen Lake Reinforcement Learning

#### Environment:
A grid-world where the agent moves through ice (safe), avoids holes (fail), and reaches the goal (success).

#### Actions:
The agent can move left, down, right, or up, with each action having consequences on the agent's state.

### TicTacToe Reinforcement Learning

#### Environment:
Implements the TicTacToe game environment using OpenAI Gym, defining rewards for wins, losses, and ties.

#### Agents:
Trains two agents separately (X and O) using Monte Carlo methods to learn optimal strategies through gameplay experience.

## Methodology

### Monte Carlo Methods

All projects employ Monte Carlo methods for policy evaluation and improvement:
- **Policy Updates**: Strategies are refined based on rewards observed during gameplay.
- **Q-Function Approximation**: Estimates expected rewards for actions taken in specific states.

## Implementation Details

Each project includes:
- **Training Functions**: Implement Monte Carlo algorithms with epsilon-greedy exploration.
- **Testing Functions**: Evaluate trained agents through simulations against random or predefined opponents.
- **Performance Evaluation**: Measures success rates, learning curves, and policy effectiveness.

## Results and Conclusion

These projects demonstrate the effectiveness of RL techniques in diverse environments:
- **Blackjack**: Learns strategies to maximize winning probabilities against a dealer.
- **Frozen Lake**: Navigates efficiently to reach the goal while avoiding pitfalls.
- **TicTacToe**: Achieves high win rates against random opponents, showcasing learned optimal strategies.

## Future Work

Further exploration could involve:
- Enhancing learning algorithms such as Q-learning or Deep Q-networks.
- Applying these methods to more complex environments or real-world applications.

## References

- Sutton, Richard S., and Andrew G. Barto. "Reinforcement Learning: An Introduction"

---

For detailed implementations and results, refer to the project repository and accompanying documentation.
