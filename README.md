# Time-Series-Forecasting
Peering into the past and predicting the future with data
I have conducted an exploratory data analysis (EDA) on a crime rate dataset and utilized Facebook Prophet for forecasting. The dataset includes details such as Case Number, Date, Block, IUCR, Primary Type, Description, Location Description, Arrest, and various geographical coordinates.

After transforming the dataset by converting 'Date' into 'ds' and crime information into 'y' is like telling the forecasting tool, in this case, Facebook Prophet, when events happen ('ds') and what we want to predict ('y') – making it easier for the tool to understand and make accurate predictions. Prophet is effective for time series forecasting due to its ability to handle seasonality, holidays, and outliers while requiring minimal data preprocessing.

The dataset's attributes provided valuable insights into crime patterns, aiding in the identification of trends and potential forecasting challenges. This approach using Facebook Prophet contributes to a robust predictive model, facilitating better-informed decision-making in crime prevention and law enforcement efforts.
