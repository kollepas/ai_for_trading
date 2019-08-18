# Alpha Research and Factor Modeling
---
> Create a statistical model using PCA. Use the model to build a portfolio along with 5 alpha factors. Evaluate these factors and optimize the portfolio accordingly.

## Overview
---
In the **Alpha Research and Factor Modeling** project a statistical risk model is built using PCA (principal component analysis). This model is used to build a portfolio along with 5 alpha factors. These factors are created and evaluated using factor-weighted returns, quantile analysis, sharpe ratio, and turnover analysis. Applying the risk model and factors, the portfolio is optimized using multiple optimization formulations. For the quadratic optimization, Python's `cvxpy` package is used. The `zipline` package will take care of the handling and accessing of the data. For the dataset, end of day quotes from Quotemedia and sector data from Sharadar are used.

## Installation
---
- Clone/Download the folder.
- Unrar the _eod-quotemeda.rar_ file located in the _data_ folder using 'Extract Here'.
- The project is in the [Jupyter Notebook file](https://github.com/kollepas/ai_for_trading/blob/master/project_04_-_alpha%20research_and_factor_modeling/project_04_-_alpha%20research_and_factor_modeling.ipynb).
- All required Python packages are stated in the [requirements.txt](https://github.com/kollepas/ai_for_trading/blob/master/project_04_-_alpha%20research_and_factor_modeling/requirements.txt) file and will be installed at the beginning of the code.

:warning: In order to use the `zipline` package, no Python version above 3.5 is accepted so far!


## How to use?
---
Open the [Jupyter Notebook file](https://github.com/kollepas/ai_for_trading/blob/master/project_04_-_alpha%20research_and_factor_modeling/project_04_-_alpha%20research_and_factor_modeling.ipynb) and run through the code blocks. The notebook itself comes with detailed explanation about each step.

## License
---
This project is licensed under the MIT License - see the [LICENSE](https://github.com/kollepas/ai_for_trading/blob/master/LICENSE) file for details.
