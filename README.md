# data_science_projects

1.[Fake Album Cover Game](https://github.com/saadkazi444/data_science_projects/blob/master/FakeAlbumCoverGame.ipynb)

In this Project we have made a random album cover page through web scrapping(This Project is from Coursera)

## Understanding what exactly we are doing:
 We are downloading a random web page from wikipedia and extracting our album title and then we are pasting the title on a random photo downloaded.
 This is what exactly our project should look like:
 
 ![Sample](https://github.com/saadkazi444/data_science_projects/blob/master/images/fakecover1.png)

## The steps followed:
 First we download a random page from wikipedia, now by using Beautiful Soup we are scarpping the 2 words from it, one for the song title and other for album title.
 The extracted word are now pasted on a random image downloaded and our final answer looks something like this:
 
 ![Sample](https://github.com/saadkazi444/data_science_projects/blob/master/images/fakecover2.png)

2. [EDA on Car Dekho Used Car Data](https://github.com/saadkazi444/data_science_projects/blob/master/eda-on-cardekho-data.ipynb)

   In this Project we have done an Exploratory analysis on Used Car Data of CarDekho, helping us understand how different cars have different depreciation and what are the factors affecting depreciation.
   
   __Depreciation__ - (Purchase Price of Car - Selling Price of Car)
   
   
   
   ## Understanding our Data:
    We initially did not had the depreciation column so we added the extra column by appplying the above formula. Then checking which car has the highest depreciation, once we have thr figures, since our dataset is small we checked whether we had enough counts for the sample we are going to select. The samples with the maximum count and maximum depreciation were selected.
    
   ## Effect of different variables on depreciation:
    On Studying our data we plotted graph of year,kms driven to see how they both affected depreciation. The result for different cars were completely satisfactory for the 2 variables.
    
   ![Sample](https://github.com/saadkazi444/data_science_projects/blob/master/images/year.png)
   
   ![Sample](https://github.com/saadkazi444/data_science_projects/blob/master/images/kms.png)
   
   Here is how kms driven and year is affecting depreciation for a particular car.
   
   Other variables sucuh as no of owners, transmission of car, fuel type does not had much impact as compared to the above 2 variables, hence it is safe to conclude that Year and Kms Driven are the 2 most important factors in deciding depreciation of used car.
   
   Let us see a pair plot of these 2 variables combined.
   
   ![Sample](https://github.com/saadkazi444/data_science_projects/blob/master/images/image1.png)
   

