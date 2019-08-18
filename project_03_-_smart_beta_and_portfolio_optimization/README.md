# Smart Beta Portfolio and Portfolio Optimization
---
> Create a smart beta portfolio (based on dividends) and calculate the performance and tracking error vs. the index. Also, optimize the portfolio and evaluate the turnover.

## Overview
---
In the **Smart Beta Portfolio and Portfolio Optimization** project, stock dividends are used as an alternative index weighting method to calculate portfolio weights. In order to check the performance of the smart beta portfolio, the annualized tracking error against the index is calculated. In the second part, the portfolio is optimized by minimizing the portfolio variance but also by closely tracking the market cap weighted index (benchmark) using Norm-2. For the quadratic optimization, Python's `cvxpy` package is used. Finally, the portfolio will be rebalanced and the corresponding portfolio turnover is being evaluated to evaluate performance. For the dataset, end of day quotes from Quotemedia are used.

## Installation
---
- Clone/Download the folder.
- The project is in the [Jupyter Notebook file](https://github.com/kollepas/ai_for_trading/blob/master/project_03_-_smart_beta_and_portfolio_optimization/project_03_-_smart_beta_and_portfolio_optimization.ipynb).
- All required Python packages are stated in the [requirements.txt](https://github.com/kollepas/ai_for_trading/blob/master/project_03_-_smart_beta_and_portfolio_optimization/requirements.txt) file and will be installed at the beginning of the code.

## How to use?
---
Open the [Jupyter Notebook file](https://github.com/kollepas/ai_for_trading/blob/master/project_03_-_smart_beta_and_portfolio_optimization/project_03_-_smart_beta_and_portfolio_optimization.ipynb) and run through the code blocks. The notebook itself comes with detailed explanation about each step.

## License
---
This project is licensed under the MIT License - see the [LICENSE](https://github.com/kollepas/ai_for_trading/blob/master/LICENSE) file for details.
