# Law Enforcement Settlement Data
## Motivation
I have been passionate about the justice system in the United States since I was in middle school. For this project, I initially had other ideas that I thought would have made stronger points. However, I could not follow through with those ideas due to lack of information, data privacy, and lack of time. When I found this dataset, I realized I wanted to take a less targeted approach and leave insights to viewer speculation. I wanted to know how these variables correlated with one another, and thought it would be interesting to know how others percieved the results. I retrieved this data from FiveThirtyEight, specifically from an article titled, "Cities Spend Millions On Police Misconduct Every Year. Here’s Why It’s So Difficult to Hold Departments Accountable." By Amelia Thomson-DeVeaux, Laura Bronner and Damini Sharma. 
A couple of years ago, I took a sociology class and learned of the inner-city cycle, which says that impoverished indivudals and families in inner cities suffer systematically. For this reason, I piqued an interest in Detroit.
## Data Sources
As stated previously, I obtained this data from an article on FiveThirtyEight. The link to the article is https://fivethirtyeight.com/features/police-misconduct-costs-cities-millions-every-year-but-thats-where-the-accountability-ends/. The actual data was provided in the following link: https://github.com/fivethirtyeight/police-settlements/.
## Data Process
In the original data, settlement information for 31 cities was provided. Each city had extensive data, so I had to narrow it down to one for this project. I chose Detroit because I have a special interest in inner-city criminal justice and opression. Data from 2010 to 2019 was provided within this file, and I chose to include data from 2017-2019. Due to the formatting of the raw data, I had to manually input each cell in Excel. The columns I chose to include were date, amount of settlement, title of settlement, and cause, but my main focus was on the zipcodes and amounts of settlements. There were several blanks in the zipcode column, as well as two settlements from Chicago that I cleared from the sheet. I also converted all columns to factors to perform analysis. After cleaning, the result was 159 entries from 2017-2019 in Detroit, MI. 
## Visualization
I chose to create a histogram using zipcodes on the x axis, and count of settlements on the y axis. As you can see, the 48100 zipcode had the highest count. This could be a cue for further research to be conducted in that area to investigate unfair behavior by law enforcement. There is also clearly a cluster of points occurring between the 48000 and 48100 areas, indicating a possible low income area and reinforcing need for further research.
![Final Zipcode Histo](https://user-images.githubusercontent.com/91650239/145518589-ab892d4d-2a7d-4c93-b06d-96b042fbc5bb.JPG)
## Analysis
I ran a correlation analysis on Zipcode and amount of settlement to see if there were any biases in certain areas. As you may have heard, laws are only laws for the poor. Law enforcement tend to exploit their power in low income areas, as that demographic is typically powerless in an encounter with the police. After running the analysis, the correlation coefficient came out to approximately -0.01. This indicates little to no relationship between the two factors. However, when I ran a group mean on amount in relation to zipcode, 48043 had a much higher mean than the others. This led me to search for outliers in my dataset for that area code. I did find several settlements in that area that were upwards of $500,000 each.
## Conclusion
Based on this analysis, there are certain areas in Detroit that are targeted by law enforcement malpractice that should be further researched. If I had more time, I would have liked to investigate deeper into this set and compare several major cities. I may pursue this endeavor in the future just for fun! I hope you enjoyed my project. Though it may not be the best, it was a labor of love. Thank you for reading!
