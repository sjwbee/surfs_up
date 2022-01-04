# Surfs Up

## Overview 

The purpose of this project is to determine weather predictions which will help to assess whether an investor will contribute to a new surf and shake shop in Hawaii. 

Because I am using Hawaii weather data stored in an SQLite database, I imported SQLalchemy to access the data through Jupyter notebook.

Looking at temperature data from both June and December, I will be able to determine whether the surf and shake shop will be profitable year round.

## Results

Deliverable 1:

<img width="590" alt="Screen Shot 2022-01-03 at 4 39 07 PM" src="https://user-images.githubusercontent.com/90734050/147994946-178dc333-5a9a-42f9-8cd8-6e4e8c480e59.png">


1. The mean and median temperature values for June are around 75 degrees (F) which will be nice surfing weather
2. The minimum temperature is 64 and the maximum is 85, so it does not get too cold or too hot during June
3. The standard deviation is 3.26, showing that the temperature stays fairly close to the average throughout the month of June. 

Deliverable 2: 

<img width="590" alt="Screen Shot 2022-01-03 at 4 45 27 PM" src="https://user-images.githubusercontent.com/90734050/147995303-daf184f2-3115-4407-a0e6-844443205a3d.png">

1. The December mean and median are around 71 degrees (F) which is slightly cooler than it is in June
2. The minimum temperature is 56 and the maximum is 83. The minimum may be too low for surfing on those days. 
3. The standard deviation is 3.75, showing the temperature stays close to 71 degrees, but it is a higher deviation than it is in June.


## Summary

Overall, the temperature appears to be suitable year-round for surfing, with a greater likelihood of cold days in December. 

To gain more information about weather data for June and December that could help determine the suitability for a surf shop that would operate year round, it would be useful to have precipitation data:

June:
  
<img width="590" alt="Screen Shot 2022-01-03 at 4 55 46 PM" src="https://user-images.githubusercontent.com/90734050/147995858-4efa1292-e67d-410e-95ff-2361656826d7.png">
  
December: 

<img width="590" alt="Screen Shot 2022-01-03 at 4 57 33 PM" src="https://user-images.githubusercontent.com/90734050/147995969-e2ab678d-88ba-4409-a755-8fe5b92a2d50.png">

Plotting the dataframe will also help show trends that could better determine how weather might affect business in the future:

June Temp:

<img width="590" alt="Screen Shot 2022-01-03 at 5 06 27 PM" src="https://user-images.githubusercontent.com/90734050/147996459-e8fe57af-2aeb-4217-89c9-fbd311bc8654.png">

December Temp: 

<img width="590" alt="Screen Shot 2022-01-03 at 5 08 22 PM" src="https://user-images.githubusercontent.com/90734050/147996578-e6547df9-476d-4fc0-b3ac-ebefdd86afc0.png">


These plots show us that June temps appear to be rising which may be good for business in that time, especially focusing on shake sales, whereas December temperatures appear more stable.




