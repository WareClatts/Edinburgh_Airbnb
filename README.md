# Edinburgh_Airbnb

1. Installation: <br>
Python3 used, libraries used = datetime, pandas, numpy, seaborn, matplotlib, statsmodels, sklearn

2. Project Motivation: <br>
This is a project to look at the Airbnb market in Edinburgh, to determine what factors are related strongly to price, what effect the Fringe Festival has, and to build a predictive model to help decide how much to charge for a particular listing.

3. File Descriptions: <br>
* calendar csvs - Detailed Calendar Data for listings in Edinburgh - found as calendar.csv.gz for various compile dates: <br>
	- calendar20200427.csv freely available from http://insideairbnb.com/get-the-data.html as of 20210613
	- calendar20210211.csv freely available from http://insideairbnb.com/get-the-data.html as of 20210613
	- calendar20210308.csv freely available from http://insideairbnb.com/get-the-data.html as of 20210613
	- calendar2019.csv freely available from https://www.kaggle.com/thoroc/edinburgh-inside-airbnb as of 20210613 <br>	
* listings csvs - Detailed Listings data - found as listings.csv.gz for various compile dates: <br>
	- listings20200427.csv freely available from http://insideairbnb.com/get-the-data.html as of 20210613
	- listings20210211.csv freely available from http://insideairbnb.com/get-the-data.html as of 20210613
	- listings20210308.csv freely available from http://insideairbnb.com/get-the-data.html as of 20210613
	- listings2019.csv freely available from https://www.kaggle.com/thoroc/edinburgh-inside-airbnb as of 20210613
* Jupyter notebook - project code for data import/wrangling/exploration and model build/testing:
	- EdinburghAirbnb.ipynb
	- Note that my environment requires a spark set-up (cell 1.1), which may not be required for other set ups and could therefore be ignored in some cases.

4. How To Interact With This Project: <br>
This is an exploratory project looking at the prices of Edinburgh lets. You can find some high-level discussion on Medium (How much is a room in Edinburgh worth?) and if you would like to use it to predict the price of your own property, please alter the values for the features after cell 4.3

5. Licensing, Authors, Acknowledgements: <br>
Airbnb data from Inside Airbnb and from Kaggle project Edinburgh Inside Airbnb by Thomas Roche. Also Udacity for resources on Githb, datasets and project structure.
