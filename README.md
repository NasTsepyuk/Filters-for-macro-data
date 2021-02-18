# Filters for macro data
Example of using Christiano-Fitzgerald, Baxter-King, Hodrick-Prescott filters in macroeconomics
## Task of the Project
1. To estimate potential output using various one-dimensional smoothing metods (filters).
2. Estimate the contributions of labor and capital to economic growth under the assumption that
potential output is described by the Cobb-Douglas production function and depends
only on labor and capital. 
3. Estimate the value of the Solow remainder.
***
## Data
Data was collected for United Kingdom from  [www.rug.nl](https://www.rug.nl/ggdc/productivity/pwt/?lang=en) which contains information about relative levels of income, output, input and productivity, covering 183 countries between 1950 and 2019.
## Variables description
In file with data `pwt100.xlsx` there are variables:
* `year` - year of observation
* `rgdpna` - Real GDP at constant 2017 national prices (in mil. 2017US$)
* `rnna` - Capital stock at constant 2017 national prices (in mil. 2017US$)
* `emp` - Number of persons engaged (in millions)

