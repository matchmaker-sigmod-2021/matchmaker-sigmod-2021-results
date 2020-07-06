# matchmaker-paper-results

In this repository is showcased the output of the [Matchmaker](https://github.com/matchmaker-sigmod-2021/matchmaker-sigmod-2021-main). 

The [output](https://github.com/matchmaker-sigmod-2021/matchmaker-sigmod-2021-results/tree/master/output) 
folder contains the zip files with the suite's output per method. 

The [Jupyter notebook](https://github.com/matchmaker-sigmod-2021/matchmaker-sigmod-2021-results/blob/master/Visualization-Final.ipynb)
 contains the code used for producing all the visualizations that accompany the paper. 
 The visualizations can be found in the [plots](https://github.com/matchmaker-sigmod-2021/matchmaker-sigmod-2021-results/tree/master/plots) folder.

#### Instructions
* Create a virtual environment

    `virtualenv matchmaker`
* Install the python packages

    `pip install -r requirements.txt`
* Unzip all the folders from the [output](hhttps://github.com/matchmaker-sigmod-2021/matchmaker-sigmod-2021-results/tree/master/output) 
and place the folders in a new one called _data_
* Run the jupyter notebook and update the path to the data folder (Step 0 in the notebook)
* Run each cell one by one until the end, where the plots are generated and saved automatically in the 
[plots](https://github.com/matchmaker-sigmod-2021/matchmaker-sigmod-2021-results/tree/master/plots) folder.