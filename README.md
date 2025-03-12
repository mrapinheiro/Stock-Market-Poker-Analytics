# Poker-Inspired Stock Trading Algorithm

## Overview
This project implements a trading algorithm based on poker decision-making strategies, applied to stock market investments. By leveraging probabilistic thinking, pattern recognition, and strategic risk management from poker, we've developed a novel approach to analyzing and predicting stock market movements.

## Features
- **Binary Outcome Analysis**: Converts monthly stock returns into binary signals (positive/negative)
- **Sequence Pattern Recognition**: Identifies recurring patterns in market movements
- **Adaptive Decision Framework**: Trading decisions based on historical pattern probabilities
- **Performance Comparison**: Benchmarking against traditional buy-and-hold strategies

## Technology Stack
- **Python 3.x**
- **Libraries**: pandas, numpy, matplotlib, yfinance
- **Data Source**: Yahoo Finance API

## Implementation Details
The algorithm works by:
1. Fetching historical stock data (focused on AAPL from 2010-2023)
2. Calculating monthly returns and converting them to binary outcomes
3. Creating decision sequences based on 3-month patterns
4. Executing trades based on identified historical patterns:
   - Buy when the previous month showed positive returns
   - Buy after two consecutive negative months (potential recovery signal)

## Results and Performance
Our analysis demonstrates that while the poker-inspired strategy provides interesting insights into market behavior, it currently underperforms compared to a simple buy-and-hold approach over the analyzed time period. This illustrates the complexity of market prediction and highlights areas for further refinement.

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/poker-trading-algorithm.git

# Install required packages
pip install pandas numpy matplotlib yfinance
```

## Usage
```python
# Run the main analysis script
python poker_trading_algorithm.py
```

## Future Work
- Extend the analysis to additional stocks and market sectors
- Incorporate more sophisticated poker concepts (e.g., pot odds, expected value)
- Implement machine learning to identify optimal pattern recognition
- Explore risk-adjusted performance metrics

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by probabilistic decision-making in poker
- Yahoo Finance for historical stock data
- Open-source Python data science community
