# Quantum Reinforcement Learning for Financial Trading💹

This project demonstrates the application of Quantum Reinforcement Learning (QRL) in financial trading. It combines quantum computing with reinforcement learning to develop adaptive trading strategies capable of real-time decision-making in volatile markets.

![image](https://github.com/user-attachments/assets/7a10542f-2209-499d-a6ef-ab1f70bc3826)


## Overview

The project leverages:
- **OpenAI's Gym**: To create a simulated trading environment.
- **Google's Cirq**: For designing and executing quantum circuits.
- **Alpha Vantage API**: To fetch historical daily stock data.

## Features

- **Adaptive Trading Strategies**: Utilizes QRL for efficient decision-making.
- **Quantum Circuit Design**: Enhances trading strategy with quantum mechanics.
- **Risk Management**: Employs an epsilon-greedy policy to balance exploration and exploitation.

![image](https://github.com/user-attachments/assets/458a58d3-35e6-4156-89d0-dab41e264c9e)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quantum-trading.git
   cd quantum-trading
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Set up your Alpha Vantage API key in `config.py`:
   ```python
   ALPHA_VANTAGE_API_KEY = 'your_api_key'
   ```

2. Run the main script:
   ```bash
   python main.py
   ```

## Results

The project evaluates the QRL model's performance using:
- Cumulative Return
- Sharpe Ratio
- Maximum Drawdown
- 
![image](https://github.com/user-attachments/assets/0b0f0f28-b6ee-4f65-ba74-225bd7df50cb)

![image](https://github.com/user-attachments/assets/3d943776-a4cc-4e8d-b6a0-0d71fc881326)

![image](https://github.com/user-attachments/assets/6ee6b3a8-930d-4369-9724-81f8225d8034)


