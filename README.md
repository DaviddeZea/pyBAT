# pyBAT: Bus line Analysis Toolkit
![alt text](https://github.com/DaviddeZea/pyBAT/blob/main/docs/pybat.png)

BAT is an open-source software to analyse bus networks through the combination of a data-driven approach and specific knowledge on bus systems from AVL data. Transit operators, researchers and practitioners alike may benefit from our contribution which fills a gap in the lack of open-source alternatives to specifically analyse bus lines. Through geospatial analysis of data, relevant KPIs, descriptive and forecasting tools are provided to properly manage historical data with a view to better manage and plan bus operations.

The structure of the software consists in a sequence of Python scripts. The params.py script comprises the set of parameters to be filled by the user before running the software. Running the main_prep.py carries out essential preprocessing tasks such as loading of datasets, cleaning of the data, feature engineering defined through simple functions in the prep.py script. Running the main_res.py script after preprocessing the raw data provides the user with the results and visualization of information specified in the params.py script. If the user wishes to compute new results, an update on the parameters is only required before running the main_res.py script again. Finally, forecasting tools are supported through the fcast.py script. A flow chart of the overall workflow can be seen in Figure 1. 

Code developer: David de Zea Graells from Barcelona Innovative Transportation (BIT), Universitat Politècnica de Catalunya (UPC-BarcelonaTech), david.de.zea@upc.edu

## Citation

## Licence
