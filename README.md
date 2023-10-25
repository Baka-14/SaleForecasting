# SaleForecasting


Summary Result - A forecasted SKU-wise sales data for each of the 76 different stores over the desired time horizon and the Result is printed in an Excel sheet with the one column indicating the Id of the product and the other column indicating the number of units sold of a particular product. There are approximately 13800 product ID’s.
One issue that we encountered during the analysis was the presence of missing data cell, particularly in the "total price" column. A specific cell within this column was marked as "N/A," signifying that the total price for that particular sale was not available or had not been recorded. Therefore, we filled the cell value with the mean of the network to replace the N/A with a value.
Another issue that we faced was the format of the "Date" variable, which was stored as a string. Therefore, we converted the week feature into week number by using the modulus operator on it by 52 and by the number of months. 
We decided to use a basic NN architecture for training our model as it provided the most accurate results compared to other models.
Validation Loss of Epoch 15 is approximately 0.3261
Training loss of Epoch 15 is approximately 0.1837
