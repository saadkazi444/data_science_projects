# data_science_projects

 1.[Fake Album Cover Game](https://github.com/saadkazi444/data_science_projects/blob/master/FakeAlbumCoverGame.ipynb)


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
   
