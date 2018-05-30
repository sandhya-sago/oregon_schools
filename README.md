
## Oregon School Data

This project gets data about School Districts (and schools) in Oregon for the years 1997-2009 from multiple sources (https://datahub.io, https://www.ode.state.or.us), cleans, cross-correlates and analyzes them.

Tools and Packages used: Python, Pandas, Matplotlib, Seaborn, Numpy, datapackage, Jupyter Notebooks.

1. [oregon_schools_eda1](oregon_schools_eda1.ipynb) 
   reads data from datahub.io. The data is relatively clean, though NAN rows had to be dropped. Various trends are visualized.
   
2. [oregon_state_report_eda2](oregon_state_report_eda2.ipynb)
    This data is downloaded as a spreadsheet from the Oregon State Education report site. The data is very unclean, with most of the columns being sparsely populated. Also, there are variations in how the school names are reported, so the data needed a lot of cleaning, and a new csv file is created.
    
3. [cross_validate_1&2](cross_validate_1&2.ipynb)
    The above two sources of data are checked against each other to make sure that the data is similar, even though the sources are different.



```python

```
