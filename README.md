<div align="center">
<h1 align="center">
<img src="" width="100" />
<br>PAIRS-TRADING-ALGORITHM</h1>
<h3>◦ Statistical Arbitrage Trading Algorithm</h3>
<h3>◦ Developed to interact with the ALPACA API with the software and tools below.</h3>
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running Pairs-Trading-Algorithm](#-running-Pairs-Trading-Algorithm)
    - [🧪 Tests](#-tests)
---


## 📍 Overview

► This Algorithm is separated into Analysis and Trading Functions.
Analysis contains the statistical methods required to implement a statistical arbitrage strategy.
Trading contains the methods that interact with the Alpaca API to execute the strategy.  
The algorithm is configured to use my ALPACA paper account API key and secret.



---

## 📦 Features

► Analysis


---


## 📂 Repository Structure

```sh
└── Pairs-trading-Algorithm/
    ├── utils/
    │   ├── my_timer.py
    │   ├── ProgressBar.py
    │   ├── formatting_and_logs.py
    ├── analysis/
    │   ├── DATES.py
    │   ├── errors.py
    │   ├── statistical_methods.py
    │   ├── stock_data.py
    │   └── visualisation.py
    ├── executors/
    │   ├── alpaca_executor.py
    │   ├── analysis_executor.py
    │   └── cli_controller.py
    ├── tests/
    │   ├── test_alpaca.py
    │   └── test_collect_metrics_for_pair.py
    ├── trading/
    │   └── alpaca_functions.py
    ├── requirements.txt
    └── to_do_list.txt

```


---


## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                               | Summary       |
| ---                                                                                                | ---           |
| [requirements.txt](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/requirements.txt) | ► Requirements needed to run program, use "pip install -r requirements.txt" |

</details>

<details closed><summary>Analysis</summary>

| File                                                                                                                  | Summary       |
| ---                                                                                                                   | ---           |
| [Visualisation.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/Analysis/visualisation.py)           | ► Functions to visualise important metrics |
| [StockData.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/Analysis/stock_data.py)                   | ► StockData class and methods |
| [Dates.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/Analysis/DATES.py)                           | ► Enum for dates |
| [StatisticalMethods.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/Analysis/statistical_methods.py) | ► Functions performing statisticaly analysis on StockData |

</details>

<details closed><summary>Tests</summary>

| File                                                                                                 | Summary       |
| ---                                                                                                  | ---           |
| [test_alpaca.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/tests/test_alpaca.py) | ► Testing the Alpaca Functions |

</details>

<details closed><summary>Executors</summary>

| File                                                                                                                 | Summary       |
| ---                                                                                                                  | ---           |
| [AnalysisExecutor.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/executors/analysis_executor.py)   | ► Executor for analysis |

</details>

<details closed><summary>utils</summary>

| File                                                                                                      | Summary       |
| ---                                                                                                       | ---           |
| [MyTimer.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/utils/my_timer.py)         | ► INSERT-TEXT |
| [ProgressBar.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/utils/ProgressBar.py) | ► INSERT-TEXT |

</details>

<details closed><summary>Trading</summary>

| File                                                                                                           | Summary       |
| ---                                                                                                            | ---           |
| [AlpacaFunctions.py](https://github.com/gelst31n/Pairs-Trading-Algorithm/blob/main/Trading/alpaca_functions.py) | ► INSERT-TEXT |

</details>

---
