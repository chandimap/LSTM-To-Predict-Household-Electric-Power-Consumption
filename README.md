# LSTM-To-Predict-Household-Electric-Power-Consumption


The dataset was downloaded from here: 
http://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

They were measurements of electric power consumption in one household with a one-minute sampling rate over almost 4 years. Different electrical quantities and some sub-metering values were available.	

The data was collected between December 2006 and November 2010 and observations of power consumption within the household were collected every minute.

It is a multivariate series comprised of seven variables (besides the date and time); they are:

•	global_active_power: The total active power consumed by the household (kilowatts).

•	global_reactive_power: The total reactive power consumed by the household (kilowatts).

•	voltage: Average voltage (volts).

•	global_intensity: Average current intensity (amps).

•	sub_metering_1: Active energy for the kitchen (watt-hours of active energy).

•	sub_metering_2: Active energy for laundry (watt-hours of active energy).

•	sub_metering_3: Active energy for climate control systems (watt-hours of active energy).

LSTM model was built to predict household electric power consumption. Dropout layers were added to improve the model.

The first year of data (resampled over an hour) was used to train the model and the rest of the data to test the model to reduce the computation time and get some results quickly.

