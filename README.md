# NYC_TAXITRIP_PREDICTION

Based on individual trip attributes, predict the duration of each trip in the test set.

File descriptions</br>
train.csv - the training set (contains 1458644 trip records)</br>
test.csv - the testing set (contains 625134 trip records)</br>
sample_submission.csv - a sample submission file in the correct format</br>

Data fields</br>
id - a unique identifier for each trip</br>
vendor_id - a code indicating the provider associated with the trip record</br>
pickup_datetime - date and time when the meter was engaged</br>
dropoff_datetime - date and time when the meter was disengaged</br>
passenger_count - the number of passengers in the vehicle (driver entered value)</br>
pickup_longitude - the longitude where the meter was engaged</br>
pickup_latitude - the latitude where the meter was engaged</br>
dropoff_longitude - the longitude where the meter was disengaged</br>
dropoff_latitude - the latitude where the meter was disengaged</br>
store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip</br>
trip_duration - duration of the trip in seconds</br>
