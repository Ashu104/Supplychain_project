## Supply Planning using Linear Programming with Python 🚛
*Where do you need to allocate your stock to meet customers' demand and reduce your transportation costs?*

<p align="center">
  <a href="https://www.samirsaci.com/supply-planning-using-linear-programming-with-python/" target="_blank" rel="noopener noreferrer">
    <img
      align="center"
      src="https://miro.medium.com/max/1280/1*y4AHwh75uQ771dEdO6sxJg.png"
      style="max-width: 100%; height: auto;"
    >
  </a>
</p>>

Supply planning is the process of managing the inventory produced by manufacturing to fulfil the requirements created from the demand plan.

Your goal is to balance supply and demand to ensure the best service level at the lowest cost.


### Problem Statement
As a Supply Planning manager at a mid-sized manufacturing company, you received feedback that distribution costs are too high.
Based on the Transportation Manager's analysis, this is primarily due to the stock allocation rules.

In some cases, your customers are not shipped by the closest distribution centre, which impacts your freight costs.


## Code
In this repository, you will find all the code used to explain the concepts presented in the article.

### Files
- `Supply Planning Problem.ipynb` - Jupyter notebook with step-by-step analysis
- `supply_planning.py` - Standalone Python script
- `data/` - Folder containing input CSV files (df_demand.csv, df_inprice.csv, df_outprice.csv)

### Getting Started
```bash
pip install -r requirements.txt
python supply_planning.py
```

### Dependencies
- pandas
- pulp
- matplotlib
- seaborn


