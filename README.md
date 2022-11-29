# Scraping, cleaning and transforming the DAI's AFE dataset
This code transforms DAI coin data to data compatible with FLAME. It scrapes from three dataframes on the DAI website: detailed results, fundort, and places. These are all separate files in the repo directory, with "afe_" prepended. The cleaning process is lengthy, resulting in two FLAME-compatible dataframes, groups and finds, prepended with "final_afe_". All data is in csv format and all code resides within the Jupyter Notebook.

DAI AFE data can be found here: http://afe.dainst.org/index.php
