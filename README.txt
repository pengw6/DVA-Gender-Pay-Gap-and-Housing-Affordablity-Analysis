Introduction:

-The dashboard was developed with Python, Excel, Alteryx and Tableau. The project aims to analyze the impact of the Gender Pay Gap (GPG) on people’s daily life by developing an open-source user interactive interface with functionalities including geographic data visualization and analytical graphs with user-defined filtering function to provide data insights.

Description: 

-Software: Excel, Alteryx and Tableau 
-Programming Language: Python
	oPackages required: pandas, PySci, Plearn, Pmdarima,matplotlib, seaborn, and numpy
	oData source: 
		Income by Gender:
		https://data.census.gov/table?q=B20002&g=0100000US$8600000
		Real Estate:
		https://redfin-public-data.s3.us-west-2.amazonaws.com/redfin_covid19/weekly_housing_market_data_most_recent.tsv000
-Download dataset files from the Data folder
-Video of installation and execution:
	ohttps://youtu.be/sJGX3ILcZL8

Installation:

You are not required to install anything prior to use the dashboard. The dashboard is hosted by Tableau server, user can directly access the dashboard with the provided URL link. We recommend openning the dashboard in Chrome using fullscreen for a better view.
If you wish to explore the code and work on top of our project, you may follow the steps below:
	1.In Python development environment, import the following Python packages: Pandas, PySci, Pmdarima, Sklearn, Matplotlib, Seaborn, and Numpy
	2.Download and import all required data files: Gender data and house data 
	3.Download and install Tableau (version 2021.4 or newer) and Alteryx.

Execution:

	1.Within Gender and House folder, follow instructions and run scripts to process data and built model.
	2.Open Alteryx and run .yxmd workflow in Gender folder to process and concatenate result data.
	3.Tableau dashboard is built based on step 4 result. Details of the dashboard can be found in the Dashboard folder.
	4.Explore Tableau dashboard online:
		oClick the provided url to visit the dashboard and interact with the dashboard features online.
		oTo bette display the dashboard and explore all features conveniently, users are recommended to use fullscreen mode in Chrome.
