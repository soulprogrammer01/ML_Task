# Task

### Data
This is a database of ~80 million Indian district court data across states from the Development Data Lab.
Please download the data (.csv format) from [here](https://www.dropbox.com/sh/hkcde3z2l1h9mq1/AAB2U1dYf6pR7qij1tQ5y11Fa/csv?dl=0&subfolder_nav_tracking=1).
To understand the tables, please refer to the metadata at the following links:
* [Act sections metadata](https://docs.google.com/spreadsheets/d/e/2PACX-1vTNxZtceqgzYlUogz-gJfMfqm-RygJZcqfZiFCQAsJYFG7BU1_ZT5aKTPrNODeDgRnoyZFBnjt2sghd/pubhtml#)
* [All cases metadata](https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vSkFghNxGjLxIAsjvUPkW8IV2AF1vf2KOQV93vMhB0TD3CBT13gah1LczI8W0d3Eom1zPcroBuPQ-uy/pubhtml#)
* [Judges metadata](https://docs.google.com/spreadsheets/d/e/2PACX-1vSqcp7VlnFB4ujCCHV5uGHjBlwYf7Mo4B3N3aqdiAukS7VMY8lLGU9ejhHH4c8qCse8l1kc8yIkCnq9/pubhtml#)

Sampling of Data :
 Done the Random sampling based upon the number of rows present in each year's dataset then merge them into one csv.
 Sampled data set has 265k rows, **download it from [here](https://drive.google.com/file/d/16qFef7lYcg6keYl8cfMIyT5_OM1yUUhE/view?usp=share_link)**
 | Year        | Initia row          | After sampling  |
| ------------- |:-------------:| -----:|
| 2010          | < 50 lakh     | 20 k |    
|2011          |  < 50 lakh    |  20 k     |
| 2012          | 50 lakh- 1cr    | 30 k |
| 2013          | 50 lakh-1cr   |    30 k|
| 2014          | 50 lakh-1cr   | 30 k |
| 2015          | 50 lakh-1cr   |   30 k |
| 2016          |  >=1 cr  |    35 k |
| 2017          | >=1.3 cr   | 35 k|
| 2018          | >=1.3 cr      |   35 k |

Refer to this [link](https://stackoverflow.com/questions/22258491/read-a-small-random-sample-from-a-big-csv-file-into-a-python-data-frame)

## Task 1
### [Analysis]() 
* #### Statewise Case Distribution. 
![observation](https://user-images.githubusercontent.com/53926096/208232233-55cfebe9-720c-4aab-8f69-49292fca5ff2.jpg)

* #### Statewise Gender Bias case Analysis.
 ![observation 2](https://user-images.githubusercontent.com/53926096/208232252-30e3eabd-563b-45c5-8a53-70d0498ba9dc.jpg)


* #### Decision time analysis
![observation3](https://user-images.githubusercontent.com/53926096/208232265-706e9e9b-97f3-4f0f-82eb-21944fd08ca1.jpg)





* #### Interesting finding 1

![insight 1](https://user-images.githubusercontent.com/53926096/208232391-c03db0a1-ce74-4ec4-9430-65f91a0b7b62.jpg)





* #### Interesting finding 2
![insight 2](https://user-images.githubusercontent.com/53926096/208232287-eaf35472-7138-418e-a327-ab68bed06d58.jpg)

## Task 2
### [Classification Model](https://github.com/soulprogrammer01/Precog_Recruitment_Task/blob/main/Modelling.ipynb) 
* To predict whether a particular defendant under a given judge will be male, female or other.
* To predict whether a particular petitioner under a given judge will be male, female or other.
#### Conclusion
![model insight](https://user-images.githubusercontent.com/53926096/208235947-f0e3ee0b-1dfa-4965-ba82-94b70c80fa5f.jpg)




