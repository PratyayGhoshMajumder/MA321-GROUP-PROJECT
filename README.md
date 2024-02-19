# CE888
I have done my code in Jupyter Notebook. In order to run the code in that IDE at first it needs to be uploaded and dataset file path needs to be provided. There is run option in that notebook and by clicking on it each chunks will run. If there is any libraries that is not installed previously then pip installing it is required.

I have used pandas library command in order to read all the dataset for the city between the year.. At first I have found descriptive statistics for this and checked the missing value present. The data contains lots of missing value and I have dropped columns which contains more than 45 percent missing values assuming that these columns are not that much important. Rest of the missing value I have used most frequent values in order to fill it and after some data visualization for the dataset is see. Finally splitting of data is done and most important features for the dataset is seen.



## ASSUMPTIONS MADE:
(a)Missing values: 'precip', 'precippro', 'precitype','snow','snowdepth', 'cloudcover','solarradiation','solarenergy', and 'uvindex' are just a few of the columns that have missing data. It is reasonable to presume that these missing values correspond to situations in which specific meteorological phenomena either did not occur or were not recorded.
(b)Temporal Resolution: The datetime field suggests that the dataset appears to be gathered hourly. It follows that each row must correspond to the meteorological conditions for a given hour.
(c)The columns which contain more than 45 percent null values is not that much importance with respect to target column and so it is being dropped.
(d)Multicollinearity: Some variables may exhibit multicollinearity, meaning they are highly correlated with each other. For example, temperature and dew point may have a strong positive correlation.

#### My next aim for the 2nd assignment is to build some time series alogrithm like ARIMA and deep learning algorithms like RNN, LSTM or any hybrid model and see how the model is performing by using evalutation metrics like RMSE,MSE and then finally forecasting the future himidity for next 1 month or so using this model.
