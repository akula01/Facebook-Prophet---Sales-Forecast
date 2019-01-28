# Facebook-Prophet---Sales-Forecast
Predicitve analytics of sales using Facebook Prophet

Facebook prophet is a procedure for forecasting time series data using daily, monthly, or yearly trends for a specific occurrence like the activity on a website or regular sales of a product at a store. Prophet requires a two-column dataframe labeled ds and y. The ds column represents the datetime variables, the date that correlates to the corresponding occurrence of the y value. This y value represents the value that the program is learning from and is ultimately predicting the value of. 

In order to develop the program I learned from a multitude of sources (as seen below) to develop a functioning model, although I did not find it to be accurate or effective. This can be attributed to the fact that the setup of our data is not proper for developing an effective model using facebook prophet. The right kind of data includes regular observations for a univariate set of data to perform the regular analysis. In order to develop the proper dataframe, after changing the column names, it is important to have the accurate date and time to represent the integer values in the y column as well as dropping all of the empty rows. Once this is complete then I am able to plug the data into the prophet model and develop a future dataset to help us test the model.

After the model has been developed and executed we can use validation techniques and performance tests to help understand and visualize the metrics of our model. These, in turn, help the program make forecasts for upcoming dates outside of the training dataset. 

