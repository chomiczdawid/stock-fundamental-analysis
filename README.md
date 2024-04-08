# Generating stock valuation report in Python

This repository contains the implementation of basic valuation measures such as fundamental analysis indicators in the form of a generated report. The algorithm supports the Polish financial reporting standard.

### Process flow:
- Historical financial statement data is scraped from the free provider's website.
- Data is converted to pandas dataframes so that calculations can be performed.
- An additional table is created with the calculated financial analysis indicators.
- Charts are drawn based on the selected indicators.
- Charts and descriptive elements are then entered into the Excel report and saved to a file.

## ToDo:
Add generation of an Excel file containing basic information about the company as well as charts and comments from the valuation.

## Used technology
- [Python version 3.8.16](https://www.python.org/)
- [Anaconda Distribution](https://www.anaconda.com/)
- [Jupyter Lab](https://jupyter.org/)

## Used libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import yfinance as yf
from datetime import date, timedelta
```
