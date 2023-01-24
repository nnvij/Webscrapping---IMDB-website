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
 
## Exploratory Data analysis:
![gross](https://user-images.githubusercontent.com/103464406/214426969-b4f34e16-f24d-4cb1-a134-d254f1cfbebc.png)
![gross_number](https://user-images.githubusercontent.com/103464406/214426522-0ab1b15c-d1c1-4e08-9413-c8c963286d21.png)
![top10_oscar](https://user-images.githubusercontent.com/103464406/214426624-133fc7ad-9b0e-485c-b270-1a89b00423bb.png)


 ## Summary:
 - Drama movies have won maximum Oscar Awards for Best Picture.
 - Action movies tend to make high revenues.
 - Average ratings for top gross movies is 7.4
 - Covid did really affect the gross margin for the movie industry
