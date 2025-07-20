<div align="center">
  <h1 align="center">Quantitative Finance Lecture Series</h1>
  <p align="center">
    A comprehensive collection of Jupyter Notebooks and resources from the Quantopian Lecture Series.
    <br />
    <a href="https://github.com/AsefAfsahi/Quantitative_Finance/issues">Report Bug</a>
    ·
    <a href="https://github.com/AsefAfsahi/Quantitative_Finance/issues">Request Feature</a>
  </p>
</div>

<div align="center">
  <a href="https://github.com/AsefAfsahi/Quantitative_Finance/stargazers"><img src="https://img.shields.io/github/stars/AsefAfsahi/Quantitative_Finance?style=for-the-badge" alt="Stars"></a>
  <a href="https://github.com/AsefAfsahi/Quantitative_Finance/network/members"><img src="https://img.shields.io/github/forks/AsefAfsahi/Quantitative_Finance?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/AsefAfsahi/Quantitative_Finance/blob/master/LICENSE"><img src="https://img.shields.io/github/license/AsefAfsahi/Quantitative_Finance?style=for-the-badge" alt="License"></a>
</div>

---

## Table of Contents

1.  [About The Project](#about-the-project)
2.  [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
3.  [Lecture Series](#lecture-series)
    * [Part 1: Foundations](#part-1-foundations)
    * [Part 2: Core Statistical Concepts](#part-2-core-statistical-concepts)
    * [Part 3: Regression Analysis](#part-3-regression-analysis)
    * [Part 4: Hypothesis Testing & Model Pitfalls](#part-4-hypothesis-testing--model-pitfalls)
    * [Part 5: Portfolio & Risk Management](#part-5-portfolio--risk-management)
    * [Part 6: Trading Strategies & Models](#part-6-trading-strategies--models)
    * [Part 7: Futures & Case Studies](#part-7-futures--case-studies)
4.  [Contributing](#contributing)
5.  [License](#license)
6.  [Acknowledgements](#acknowledgements)

---

## About The Project

<a href="https://www.quantopian.com/lectures"><img src="http://i.imgur.com/KzPuAuJ.png" align="right" width="300"></a>

This repository is a curated collection of the **Quantopian Lecture Series**, providing a structured learning path for quantitative finance. It is designed for both beginners and experienced individuals looking to solidify their understanding of financial markets through a data-driven, programmatic approach.

The materials cover everything from Python fundamentals to advanced topics like algorithmic trading, portfolio optimization, and risk management. Each lecture is a self-contained Jupyter Notebook, combining theory with executable code for a hands-on learning experience.

### Key Features:
* **Comprehensive Curriculum:** 56 lectures covering a wide array of quant finance topics.
* **Hands-On Learning:** Jupyter Notebooks with practical code examples.
* **Video Content:** Links to video lectures for many of the topics.

---

## Getting Started

To get a local copy of these lectures up and running, follow these simple steps.

### Prerequisites

You will need Python 3.x and pip installed on your system. It is highly recommended to use a virtual environment.

* **Python:** [Download Python](https://www.python.org/downloads/)
* **Virtual Environment (Recommended):**
    ```sh
    python -m venv quant-env
    source quant-env/bin/activate  # On Windows use `quant-env\Scripts\activate`
    ```

### Installation

1.  Clone the repository:
    ```sh
    git clone [https://github.com/AsefAfsahi/Quantitative_Finance.git](https://github.com/AsefAfsahi/Quantitative_Finance.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd Quantitative_Finance/
    ```
3.  Install the required Python packages:
    ```sh
    pip install numpy pandas matplotlib scipy scikit-learn statsmodels alphalens jupyter
    ```
4.  Start Jupyter Notebook to explore the lectures:
    ```sh
    jupyter notebook
    ```

---

## Lecture Series

The lecture series is broken down into thematic sections to guide your learning.

### Part 1: Foundations

| # | Topic | Notebook | Video |
|---|---|---|---|
| 1 | Introduction to Research | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Research) | [▶️](http://googleusercontent.com/youtube/com/0) |
| 2 | Introduction to Python | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Python) | [▶️](http://googleusercontent.com/youtube/com/1) |
| 3 | Introduction to NumPy | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_NumPy) | [▶️](http://googleusercontent.com/youtube/com/2) |
| 4 | Introduction to pandas | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Pandas) | [▶️](http://googleusercontent.com/youtube/com/3) |
| 5 | Plotting Data | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Plotting_Data) | [▶️](http://googleusercontent.com/youtube/com/4) |

### Part 2: Core Statistical Concepts

| # | Topic | Notebook | Video |
|---|---|---|---|
| 6 | Means | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Means) | [▶️](http://googleusercontent.com/youtube/com/5) |
| 7 | Variance | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Variance) | [▶️](http://googleusercontent.com/youtube/com/6) |
| 8 | Statistical Moments | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Statistical_Moments) | [▶️](http://googleusercontent.com/youtube/com/7) |
| 9 | Linear Correlation Analysis | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Linear_Correlation_Analysis) | [▶️](http://googleusercontent.com/youtube/com/8) |
| 10 | Instability of Estimates | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Instability_of_Estimates) | [▶️](http://googleusercontent.com/youtube/com/9) |
| 11 | Random Variables | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Random_Variables) | |

### Part 3: Regression Analysis

| # | Topic | Notebook | Video |
|---|---|---|---|
| 12 | Linear Regression | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Linear_Regression) | [▶️](http://googleusercontent.com/youtube/com/10) |
| 13 | Maximum Likelihood Estimation | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Maximum_Likelihood_Estimation) | |
| 14 | Regression Model Instability | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Regression_Model_Instability) | [▶️](http://googleusercontent.com/youtube/com/11) |
| 15 | Multiple Linear Regression | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Multiple_Linear_Regression) | |
| 16 | Violations of Regression Models | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Violations_of_Regression_Models) | [▶️](http://googleusercontent.com/youtube/com/12) |
| 17 | Model Misspecification | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Model_Misspecification) | [▶️](http://googleusercontent.com/youtube/com/13) |
| 18 | Residual Analysis | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Residuals_Analysis) | |

### Part 4: Hypothesis Testing & Model Pitfalls

| # | Topic | Notebook | Video |
|---|---|---|---|
| 19 | The Dangers of Overfitting | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/The_Dangers_of_Overfitting) | [▶️](http://googleusercontent.com/youtube/com/14) |
| 20 | Hypothesis Testing | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Hypothesis_Testing) | |
| 21 | Confidence Intervals | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Confidence_Intervals) | |
| 22 | p-Hacking & Multiple Comparisons | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/p-Hacking_and_Multiple_Comparisons_Bias) | [▶️](http://googleusercontent.com/youtube/com/15) |
| 23 | Spearman Rank Correlation | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Spearman_Rank_Correlation) | [▶️](http://googleusercontent.com/youtube/com/16) |

### Part 5: Portfolio & Risk Management

| # | Topic | Notebook | Video |
|---|---|---|---|
| 24 | Leverage | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Leverage) | |
| 25 | Position Concentration Risk | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Position_Concentration_Risk) | [▶️](http://googleusercontent.com/youtube/com/17) |
| 26 | Estimating Covariance Matrices | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Estimating_Covariance_Matrices) | |
| 30 | CAPM and APT | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/CAPM_and_Arbitrage_Pricing_Theory) | |
| 31 | Beta Hedging | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Beta_Hedging) | [▶️](http://googleusercontent.com/youtube/com/19) |
| 32 | Fundamental Factor Models | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Fundamental_Factor_Models) | [▶️](http://googleusercontent.com/youtube/com/20) |
| 33 | Portfolio Analysis | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Portfolio_Analysis) | |
| 34 | Factor Risk Exposure | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Factor_Risk_Exposure) | [▶️](http://googleusercontent.com/youtube/com/21) |
| 35 | Risk-Constrained Optimization | [📝](https://github.com/quantopian/research_public/blob/master/notebooks/lectures/Factor_Based_Risk_Management/notebook.ipynb) | |
| 36 | Principal Component Analysis | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/PCA) | |
| 42 | VaR and CVaR | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/VaR_and_CVaR) | |

### Part 6: Trading Strategies & Models

| # | Topic | Notebook | Video |
|---|---|---|---|
| 27 | Volume, Slippage, and Liquidity | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Volume_Slippage_and_Liquidity) | |
| 28 | Market Impact Models | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Market_Impact_Model) | |
| 29 | Universe Selection | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Universe_Selection) | [▶️](http://googleusercontent.com/youtube/com/18) |
| 37 | Long-Short Equity | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Long-Short_Equity) | |
| 38 | Example: Long-Short Algorithm | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Long-Short_Equity) | |
| 39 | Factor Analysis with Alphalens | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Factor_Analysis) | [▶️](http://googleusercontent.com/youtube/com/22) |
| 43 | Cointegration and Stationarity | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Integration_Cointegration_and_Stationarity) | [▶️](http://googleusercontent.com/youtube/com/23) |
| 44 | Introduction to Pairs Trading | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Pairs_Trading) | [▶️](http://googleusercontent.com/youtube/com/24) |
| 45 | Example: Basic Pairs Trading | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Pairs_Trading) | |
| 47 | Autocorrelation and AR Models | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Autocorrelation_and_AR_Models) | [▶️](http://googleusercontent.com/youtube/com/25) |
| 48 | ARCH, GARCH, and GMM | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/ARCH_GARCH_and_GMM) | |
| 49 | Kalman Filters | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Kalman_Filters) | [▶️](http://googleusercontent.com/youtube/com/26) |
| 50 | Example: Kalman Filter Pairs Trade | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Kalman_Filters) | |

### Part 7: Futures & Case Studies

| # | Topic | Notebook | Video |
|---|---|---|---|
| 51 | Introduction to Futures | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Futures) | |
| 52 | Futures Trading Considerations | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Futures_Trading_Considerations) | |
| 53 | Mean Reversion on Futures | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Mean_Reversion_on_Futures) | |
| 54 | Example: Pairs Trading on Futures | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Introduction_to_Pairs_Trading) | |
| 55 | Case Study: Value Factor | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Case_Study_Traditional_Value_Factor) | |
| 56 | Case Study: Comparing ETFs | [📝](https://github.com/AsefAfsahi/Quantitative_Finance/tree/master/Quantopian/Lecture/Case_Study_Comparing_ETFs) | |

---

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## Acknowledgements

* This content is based on the original lecture series created by **Quantopian**.
* Thanks to all contributors who maintain and improve this repository.
