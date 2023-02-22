# Mod11challenge

This is a python script that uses Facebook Prophet to predict google searches.
The script uses "google_hourly_search_trends.csv", "mercado_daily_revenue.csv", and "mercado_sotck_price.csv" to compile the data.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For access to Pandas series and dataframes.

* [pathlib](https://github.com/budlight/pathlib) - To load csv files.

* [hvplot.pandas](hvplot.pandas) - To plot data.

* [Prophet](https://facebook.github.io/prophet/) - To use the prophet forecasting model.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
from pathlib import Path
import numpy as np
```

---

## Usage

To use the script simply clone the repository and forecasting_net_prophet.ipynb

```python
forecasting_net_prophet.ipynb
```



---

## Contributors

Mike Blanchette

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
