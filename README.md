# Udemy Financial Analysis

Notes from a Udemy course for financial analysis using Python.

This repository contains:

1. The repository requirements in `requirements.txt`
2. Jupyter Notebook lecture notes in `project/*.ipynb` organized by section
3. A static HTML webpage of the notes in `project/*.html` also organized by section
4. Figures used by the notebooks and webpages in `project/jupyter-figures`
5. Miscellaneous stock data in `project/data` analyzed in the lecture notes



## Table of Contents

- [Background](#background)
- [Usage](#usage)



## Background

[Udemy](https://www.udemy.com) provides short inexpensive online courses on a wide variety of topics. In the course *Python for Finance: Investment Fundamentals & Data Analytics*, created by 365 Careers, essential and advanced skills for analyzing investments are explored.

In the first section of the course, the simple and logarithmic rates of return (RORs) of investments are explored in detail as well as the rates of return for both portfolios and indices.

Equiped with a basic understanding of upside potential, the course dives into financial risk management techniques in the second section using the standard deviations and variances of individual securities. In order to minimize the risk of an investment portfolio, the distinction between diversifiable and un-diversifiable risks is explored and risk is minimized in a portfolio using the covariance and correlation of its constituent securities.

Section three covers simple regression while section six covers multivariate regression for modeling complex systems such as the pricing of homes and other assets.

Expanding on the concepts of portfolio optimization, section four outlines the theory and implementation of Markowitz efficient portfolios. The efficient frontier is calculated for a portfolio containing two stocks. The efficient asset allocation strategy if outlined in the form of coefficients denoting how much money should be dedicated to each stock in the portfolio.

The level of acceptable risk in a portfolio is relative but the theoretical balance of risk and return is outlined in section five through the capital asset pricing model (CAPM). The beta of a security is discussed along with the Sharpe ratio. The optimal expected return of a portfolio is obtained using the 10-year treasury note as a risk free asset in CAPM's modeling.

Finally, Monte Carlo analysis is demonstrated in section seven as a method for estimating the value at risk (VAR) for a security.


## Usage

Install the requirements in a python environment using the included requirements file. Then navigate to the project directory

```sh
pip install -r requirements.txt
```

Using a JupyterLab session, you may interact with the course notes.

**Warning:** the Pandas data reader has been depricated. Future use of this code will require another data source.
