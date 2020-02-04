# Udacity-Data-Scientist---Project-4-Blog-Post
Code behind the blog post for Udacity Data Scientist Project 4 - Create a blog post. 

Blog post can be found at: https://medium.com/@andrew.goode_70135/ecological-carbon-deficit-are-we-doomed-7550d8a2fd42

File: Project 4 - Data Science.ipynb
Libraries used: Pandas
                Matplotlib
                Numpy
                
Data sources:
NFA 2018.csv: https://www.kaggle.com/footprintnetwork/national-footprint-accounts-2018
UNCountry_LandSize.csv: http://data.un.org/Data.aspx?d=FAO&f=itemCode:6601
Happiness2012.csv: https://photius.com/rankings/happiness_country_rankings_2012.html

Motivation:
As part of Udacity's Data Scientist nanodegree I was required to investigate a data-set and write a blog post about my findings. 

I have chosen to investigate trends in ecological surplus and deficits across the different countries. 

Questions cosnsidered were:
1. How does population affect biocapacity and carbon emmisions? Test the theory that increase in population results in a decrease in biocapacity. (Total and per capita). 

2. Which countries have the biggest deficit? Is there a correlation between GDP per capita and carbon deficit?

3. What are the global trends? Are countries increasing or decreasing their deficit year on year?

4. Is Biocapacity decreasing, or carbon footprint increasing, or both? 

5. Compare to the global happiness index. Look specifically in Europe. Data only available for 2012 

Conclusions:
1. Increase in population is not related to a country's biocapacity. 
2. a) Per capita, oil rich countries such as Qatar, UAE, Kuwait have the highest deficit. Luxembourg and Belgium are also in the top 10 (Luxembourg 2, Belgium 9). 
   b) For total deficit, China, USA and India have the biggest absolute deficit. 
3. Globally the deficit is increasing. Western countries such as USA, UK, Germany are all reducing deficit now. China has been increasing until recently, with a small dip towards the end of the data time period. India appears to be increasing the deficit at an accelerating rate. 

4. Globally, biocapacity and carbon footprint are both increasing, but carbon footprint at a fast rate. Per capita, biocapacity is reducing while carbon footprint is increasing. 

5. Global happiness did not appear to be linked to ecological deficit, or biocapacity. It appears to be linked to GDP, which in turn is linked to carbon footprint. 
