# Webscrapping---IMDB-website
## Introduction:
- IMDB is an online database of information on films, television series and video games founded by Col needham in 1990. It os now a subsidiary of Amazon. 
- They have currenty 8.7 million titles, 11.4 million person records and 83 million registered users
## Goals:
- Webscrape movie data from https://www.imdb.com/
- Perform exploratory data analysis on the data collected 
### Tools used:
•	Beautiful Soup, Selenium (data collection)
•	Pandas (data processing)
•	Matplotlib, Seaborn
## Data:
### Data Collection:
- Collected 10,000 movie title using function inputMovieData(), data was saved to Moviedataframe (shape :(10049, 11))
- 94 Bestpicture data was collected using function InputSearchResultpage() and saving them into  dataframe BestPictureadatframe (shape :(94,11))

  ![image](https://user-images.githubusercontent.com/103464406/214417720-a2440f45-3573-4101-98f4-7b268f92d062.png)
  ![image](https://user-images.githubusercontent.com/103464406/214418848-512de7cc-768b-446a-aa99-e2c4fd84ffb8.png)
  ![image](https://user-images.githubusercontent.com/103464406/214419053-a2249ba3-2ab0-4704-b32a-beb7dfe286d9.png)

 ### Data Cleanning:
 - Used regular expression to extract Year, Gross from respective columns.
 - Converted columns Year, Runtime, Rating, Votes,Gross from String to numeric.
 - Removed null values
 
 ### Exploratory Data analysis:
    - Performed EDA on the data collected using plotlyexpress,seaborn
    
    ![image](https://user-images.githubusercontent.com/103464406/214424391-aa63ab77-dc03-4521-9dfa-a82c188468b4.png)
    
    ![image](https://user-images.githubusercontent.com/103464406/214424606-efc044a1-38f4-465b-ba4c-ec65369b993f.png)
    
    ![image](https://user-images.githubusercontent.com/103464406/214425024-e6450e25-9103-4910-921c-85486f405633.png)


 ## Summary:
    Based on the data collected 
    - Drama movies have won maximum Oscar Awards for Best Picture.
    - Action movies tend to make high revenues.
    - Average ratings for top gross movies is 7.4
    - Covid did really affect the gross margin for the movie industry
