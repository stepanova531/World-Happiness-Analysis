# World-Happiness-Analysis
Data analysis of the factors that contribute the most to the happiness level
# Objective
To explore the trends in happiness and which factors contribute the most to the happiness level.
# Scenario
Many people would like to move to another country for a long term without establishing permanent residency there. Among their objectives, there are traveling, working, studying, and temporary stay in a country with comfortable climate, but all of them give their preference to a country where the living conditions will contribute to their happiness. 
There are two main categories: retired people, whose main criteria are safety, good social relationships and access to high quality medical services. Another group is young people and their demands are good salary, low costs of living and freedom of choice.  
# Data
Open source data: World Happiness Report.
The World Happiness Report is a partnership of Gallup, the Oxford Wellbeing Research Centre, the UN Sustainable Development Solutions Network, and the WHR’s Editorial Board.
Merged dataset is based on country results for 9 years since 2015 to 2023 in a prepared datasets and allows to conduct spatial and time series analysis.
Data is available [here](https://www.kaggle.com/datasets/unsdsn/world-happiness).
# Data cntents
The data is categorized by country for 2015-2023 and contains the following variables: Happiness rank, Happiness score, GDP per capita, Family / social support, Healthy life expectancy, Freedom to make life choices, Generosity (willingness to donate for charity), Perceptions of corruption.
# Tools
Python, Jupyter Notebook, Pandas & NumPy Libraries, Matplotlib, Seaborn, Tableau
# Insights and Recommendations
  For retired people aiming at traveling or temporaryly staying in different countries for a long term and based on their preferences of good relationships and excellent medical services, the relationship between happiness score and two happiness factors life expectancy and social support have been analyzed.  
- Both factors have positive and strong correlation with the happiness score. 
- Nations with the highest life expectancy score are not classified as the happiest counties. While family and social support contribute a lot to the people’s happiness in the counties from the top-20 list. 
- I would suggest that elderly people select a country of their destination from the top happiest counties and with a high social relationship level. 
#
For the younger generation, whose purposes in life are traveling & working or studying outside of the country of their residency and who defined their values as high paid salary and freedom, I have analyzed how GDP per capita and freedom of choice are correlated with the happiness score. 
- GDP per capita has the strongest correlation. Freedom has weaker, but still positive correlation.   
- The highest level of GDP isn’t always compatible with the high happiness level. Moreover, five countries out of ten that reported the highest GDP score are ruled by autocratic governments. It is very unlikely that young people will be happy to stay there for a long term.        
- I would recommend that young people select a country of their destination from the top happiest counties and with a high freedom level. 
# Key takeaways
- For successful supervised machine learning, we need to feed enough data to predict the outcome, use statistics (regression coefficient, MSE, R2 score) to assess accuracy; the model shouldn’t be overfitted; the performance  can be improved by removing outliers.
- For clustering / unsupervised machine learning, the main steps of analysis are standardizing data, defining the number of clusters, analyzing the individual statistics of each cluster. 
- For time series analysis: only stationary data can be used for forecasting; by decomposing the data we can analyze three main components: trend, seasonality and noise. Statistical test check should be used in combination with other technics to check the data stationarity. 
