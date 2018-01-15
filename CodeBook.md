# Code Book

This code book summarizes the resulting data fields in `tidy.txt` file.

##Variables and Descriptions

* `subject` - ID the subject who performed the activity for each window sample. Its range is from 1 to 30.
* `activity` - Activity name
* `featDomain` - Feature: Time domain signal or frequency domain signal (Time or Freq)
* `featInstrument` - Feature: Measuring instrument (Accelerometer or Gyroscope)
* `featAcceleration` -  Feature: Acceleration signal (Body or Gravity)
* `featVariable` - Feature: Variable (Mean or SD)
* `featJerk` - Feature: Jerk signal
* `featMagnitude` - Feature: Magnitude of the signals calculated using the Euclidean norm
* `featAxis` - Feature: 3-axial signals in the X, Y and Z directions (X, Y, or Z)
* `featCount` - Feature: Count of data points used to compute `average`
* `featAverage` - Feature: Average of each variable for each activity and each subject

## Activity Labels

* `WALKING` (value `1`): subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
* `SITTING` (value `4`): subject was sitting during the test
* `STANDING` (value `5`): subject was standing during the test
* `LAYING` (value `6`): subject was laying down during the test


