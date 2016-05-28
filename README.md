# Analysis for safer roads

## Synopsis
While I was driving in Japan one day, I have found myself wondering if the color of a car had any impact on its probably to be into an accident.
If a car is bright red in a country where most cars are white, black, or grey, then I would expect it to be more noticeable and hopefully less involved in car accidents.

I unfortunately haven't found data containing the color of the cars involved in accidents.
Insurance companies do apply a premium to red cars but it could be for a higher risk of theft and not car accidents.

I have discover the very detailed records on the car accidents happening in France collected by the French interior ministry.
They are so far the best I have found and I have decided to in details at these records to get a better understanding of the factors leading to accidents.
I really wonder if there are some practices that could reduce the risk of an accident.
For example:
- Is it safer to walk on the side of the road facing the incoming cars or turning our backs to them ?
- Is the public lighting system sufficient or are the accidents still occuring mostly in poorly lit roads ?
- Does daylight saving help reduce or increase the number of accidents ?
- Can we predict the gravity of an accident based on basic information, maybe to guide emergency response teams ?

The data was obtain from the French government open data website under the Open Licence.
https://www.data.gouv.fr/fr/datasets/base-de-donnees-accidents-corporels-de-la-circulation/


## Outline
1. [Section1 - Data wrangling](https://github.com/hillairet/analysis-for-safer-roads/blob/master/Section1%20-%20Data%20Wrangling.ipynb)
2. Section2 - Data visualization
	* [a - Time dependence](https://github.com/hillairet/analysis-for-safer-roads/blob/master/Section2a%20-%20Data%20Visualization.ipynb)
	* [b - Who is involved in accidents](https://github.com/hillairet/analysis-for-safer-roads/blob/master/Section2b%20-%20Data%20Visualization.ipynb)
3. Section3 - Predict gravity
	* a - Preparation of features and target
	* b - Machine learning


## Software used
- Jupyter Notebook
- Python with various modules:
  * Pandas
  * Matplotlib
  * Seaborn
- MariaDB database
