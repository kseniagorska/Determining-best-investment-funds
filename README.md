# Determining best investment funds
This project evaluates four new investment options for inclusion in the client portfolios. It determines the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.
This Jupyter notebook contains the  data preparation, analysis, and visualizations for key risk and return metrics. 

## The dataset 

The dataset contains NAV prices of the four portfolios:SOROS FUND MANAGEMENT LLC, PAULSON & CO.INC.,TIGER GLOBAL MANAGEMENT LLC, BERKSHIRE HATHAWAY INC, and the closing prices of the S&P 500 Index. The data covers the period of 2014-10-01 till 2020-09-11.

## Technologies
This project leverages python 3.7 with the following packages:
* Pandas - for financial calculations
* Path - for identifying the file
* Matplotlib - for creation of visual graphs
* Numpy - for complicated mathematical functions
* Seaborn- for statistical data visualization


---

## Installation guide
Install the following dependencies
```python
pip install pandas
conda install matplotlib
conda install seaborn -y

```
## Examples

![rolling_std](rolling_std.png)

---

![sharpe_ratios](sharpe_ratios.png)

---

![rolling_beta](rolling_beta.png)

---

![rolling_beta_tiger](rolling_beta_tiger.png)

---


## Contributors

Brought to you by Ksenia Gorska as part of the UC Berkeley Extension Bootcamp: UCB-VIRT-FIN-PT-06-2021-U-B-MW Ksenia Gorska
 e-mail: kseniagorska@icloud.com 
[linkedin] (https://www.linkedin.com/in/ksenia-gorska/)

## License

MIT
