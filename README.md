# Bryan Johnson's GWU Module 11 Webscraping Assignment READ ME File

## The files for this assignment can be found at the following repo:
https://github.com/bryanpijohnson/webscraping-challenge

## Within the repo link, you will find the following folders and files to be reviewed and graded:

- **README.md** - that is this file. :)
- **Mars Files** - this is the folder where the following files live
    - **part_1_mars_news.ipynb** - this file is the 1st part of the challenge
    - **part_2_mars_weather.ipynd** - this file is the 2nd part of the challenge
    - **mars_info.json** - this is the optional json we were told to create in the 1st part of the challenge
    - **mars_data.csv** - this is the data file we were told to create
    - **.gitignore** - I have the initial files from the starter code saved to be referenced in case I make a mistake in the real file

---
### Assignment Questions

The assignmented asked us to answer 5 questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    - Find the average minimum daily temperature for all of the months.
    - Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    - Find the average daily atmospheric pressure of all the months.
    - Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    - Visually estimate the result by plotting the daily minimum temperature.

Afterwards, expert the DataFrame to a CSV file.

---
### Assessment Answers

1. By grouping by "month" and getting a count, we see that there are 12 months on Mars.
2. We can either count how many distinct rows there are, but there could be multiple days with data. Instead, I opted to look at the count of unique "sols" to see how many unique days there are.
3. Generally speaking, the average minimum temperature is very cold. The data shows that the 3rd month is the coldest, at -83.3 degrees Celsius, and the 8th month is the *warmest*, at -68.4 degrees Celsius.
![Average Monthly Low Temperature on Mars]("Mars Files/Images/avg_low_temp_mars.png")


---

If you have any questions, please feel free to contact me.