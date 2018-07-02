# Data_Manipulation_Attendance-Sheet
So, There was a time when I were to upload attendance for our colleagues in HRMS portal manually. we needed to upload employee attendance in our portal in a format which accepts date in 'dd/mm/yyyy' format and time in 'hh:mm' format.
With the help of 'pandas' and 'datetime' library I were able to manipulate the data from Biometric logs and write a CSV file which is in the format that HRMS accepts.


The LogDate folder contains the entries in 'mm/dd/yyyy hh:mm:ss' format.

Step 1:
from the Biometric logs, select the required columns 

Step 2:
filter out the rows for the dates attendance to be uploaded

Split 3:
split the date and time

Step 4:
change the date format to 'dd/mm/yyyy'

Step 5:
change the time format to 'hh:mm'

Step 6:
Select the first and last entries for one employee as there can be more than one entries due to lunch break etc.

Step 7:
create the final DataFrame

Step 8:
Write CSV
