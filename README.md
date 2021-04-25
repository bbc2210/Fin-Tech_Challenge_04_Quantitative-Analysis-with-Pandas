# Quantitative-Analysis-with-Pandas

You'll assume the role of a quantitative analyst for a FinTech investing platform. This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality. (Think about [Wealthfront (Links to an external site.)](https://www.wealthfront.com/) or [Betterment (Links to an external site.)](https://www.betterment.com/)). To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.

You've been tasked with evaluating four new investment options for inclusion in the client portfolios. Legendary fund and hedge-fund managers run all four selections. (People sometimes refer to these managers as **whales** because of the large amount of money that they manage). You’ll need to determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

![std_portfolios_rolling_window](Images/std_portfolios_rolling_window.png)



---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://pandas.pydata.org/) - Pandas is a Python library that’s designed speci cally for data analysis. It offers a streamlined way of reviewing datasets and includes
  various functions that simplify importing, updating, and analyzing data.

* [JupyterLab](https://jupyter.org/) - JupyterLab is a web-based user interface that you use to run and review Python-based programs. It easily integrates with the Anaconda
  software package and your Conda development environment.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
sourse activate 
conda activate dev
conda list pandas
conda list jupyterlab
conda deactivate
conda remove --name dev --all
conda info --envs
conda update conda
conda create -n dev python=3.7 anaconda
python -m pip install pandas
pip install jupyter 
#check if pandas is installed successfully
conda list pandas
#check if jupyterlab is listed successfully
conda list jupyterlab
```

---

## Usage

To use the Crypto Arbitrage application simply clone the repository, download whale_navs.csv,   and run the **risk_return_analysis.ipynb** with:

```python
jupyter lab
```

---

## Contributors


---

## License