# q-learning

> Q-Learning Reinforcement Learning Implementation

![Language](https://img.shields.io/github/languages/top/J1u2a3n8/q-learning)
![License](https://img.shields.io/github/license/J1u2a3n8/q-learning)
![Last Commit](https://img.shields.io/github/last-commit/J1u2a3n8/q-learning)
![Stars](https://img.shields.io/github/stars/J1u2a3n8/q-learning?style=social)
![Issues](https://img.shields.io/github/issues/J1u2a3n8/q-learning)

## Description

From-scratch implementation of Q-Learning algorithm with epsilon-greedy exploration, experience replay, and visualization of learning curves. Includes GridWorld and custom environment examples.

## Architecture

RL Loop: Environment → Agent (Q-Table/Neural Net) → Action → Reward → Update → Repeat

## Quick Start

### Prerequisites

Python 3.10+, pip/poetry, Jupyter Lab

### Installation

```bash
# Clone
git clone https://github.com/J1u2a3n8/q-learning.git
cd q-learning

pip install -r requirements.txt
# jupyter lab
```

### Usage

```bash
jupyter notebook notebooks/q-learning-demo.ipynb
```

## Testing

```bash
pytest tests/
```

## Project Structure

```
q-learning/
├── src/              # Main source code
├── tests/            # Unit/integration tests
├── docs/             # Documentation
├── .github/          # CI/CD workflows
└── README.md
```

## Tech Stack

Python, NumPy, Matplotlib, Gym/Gymnasium, Jupyter

## License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

## Author

**J1u2a3n8** - [GitHub](https://github.com/J1u2a3n8) - [LinkedIn](https://www.linkedin.com/in/juan-luis-canedo-villarroel-189783227/)

---

⭐ If you found this project useful, give it a star!
