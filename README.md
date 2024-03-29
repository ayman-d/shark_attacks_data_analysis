# shark_attacks_data_analysis
This is a data analysis project for the data collected of shark attacks since 1900 to early 2000s

I went through the process of data importing, data cleansing and wrangling, visualization and conclusions, and finally applied a logistic regression model to predict certain outcomes from the data.

To view the project please either view it locally on github, or download jupyter notebook to view the file on a web page as intended.

Jupyter Notebook Installation
kindly follow instructions on this link: https://jupyter.readthedocs.io/en/latest/install.html

Once installed and jupyter is launched, please navigate to the file and run it in notebook to see the full page.

To view the file kindly click on the the jupyter notebook file in the reporsitory. Make sure to select the file with the .ipynb extension

If github does not render the file internally, please go to https://nbviewer.jupyter.org/ and in the location bar in the main page paste the address for the jupyter notebook: https://github.com/aymand1982/shark_attacks_data_analysis/blob/master/shark_attacks.ipynb

-----

18/10/2019

- Added an interactive world map to the file that shows the number of shark attacks pertaining to the country that is hovered over with mouse, map can also be zoomed in and out.

- Added the new excel sheet I used to add the country codes which can be used to make the map.

![](map.jpg)

-----

Project Files:

- shark_attacks.ipynb: main jupyter notebook project file.
- sharks.xlsx: this is the file that contains the original data set I used for this project.
- sharks_adjusted.xlsx: this is the file I used to adjust the 'Activity' column and group them all under 6 categories.
- new_map_df.xlsx: this is the file where I extracted the data of countries and the number of attacks in each country, I then added the country codes so that this data frame can be used to make the interactive map.
