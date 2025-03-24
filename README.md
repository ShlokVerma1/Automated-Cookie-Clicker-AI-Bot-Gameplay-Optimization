# Automated-Cookie-Clicker-AI-Bot-Gameplay-Optimization

## Overview

The **Automated Cookie Clicker AI Bot** is designed to automate repetitive gameplay in the popular online game, Cookie Clicker. This AI bot leverages a greedy algorithm to optimize in-game purchases and enhance player efficiency while significantly reducing the necessity of manual clicking. The bot has proven its effectiveness by executing successful gameplay across 20 instances, streamlining the player’s experience.

## Table of Contents

* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [How it Works](#how-it-works)
* [License](#license)

## Features

* Automates the clicking process to eliminate 95% of repetitive actions.
* Implements a greedy algorithm to make optimal purchasing decisions in the game.
* Enhances gameplay experience and reduces effort required to progress.

## Installation

To set up the Automated Cookie Clicker AI Bot, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Automated-Cookie-Clicker-AI-Bot.git
    ```
2. Navigate into the project directory:

    ```bash
    cd Automated-Cookie-Clicker-AI-Bot
    ```
3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once installed, you can run the AI bot with the following command:

```bash
python bot.py
```

### Configuration

Before running the bot, you may need to configure certain parameters in the `config.json` file, such as:

* `click_interval`: The time interval between cookie clicks.
* `purchase_strategy`: The criteria used for purchasing accessories (e.g., greedy, optimal).

## How it Works

The bot uses a greedy algorithm approach to optimize in-game actions by:

1. **Clicking the Cookie**: The CPU automates clicks at the specified interval to collect points continuously.
2. **Evaluating Purchases**: The bot analyzes available accessories based on their cost-effectiveness and prioritizes those that provide the highest return on investment (ROI).
3. **Making Purchases**: Once enough points are accumulated, the bot purchases the optimal accessories, filtering out overpriced options.

### Example of Configuration JSON

```json
{
  "click_interval": 0.1,
  "purchase_strategy": "greedy"
}


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
