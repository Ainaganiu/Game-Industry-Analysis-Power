# ANALYTICS CORPER WORKSHOP DATA CHALLENGE REPORT
----
## INDUSTRY ANALYSIS
-----------------

The gaming industry is an industry categorized as entertainment and has a market size of $249.60bn. The global video game industry is a billion-dollar business and has been for many years. In 2022, the revenue from the worldwide gaming market was estimated at almost 347 billion U.S. dollars, with the mobile gaming market generating an estimated 248 billion U.S. dollars of the total.

**The Top Players in this Industry**

The Big 3 in the video gaming industry are Nintendo, Microsoft, and Sony. These three companies are major video gaming hardware makers and currently dominate the console gaming market. Due to this infrastructure advantage, the Big 3 are the biggest video game publishers worldwide, making billion of U.S. dollars from video games every year.

**Market Size**

The total demand for gamers in 2023 is estimated to be around 3.3 billion users. As the rate that games are being developed increases each day, the gaming industry shows no sign of slowing down any time soon.

# OBJECTIVE OF THE ANALYSIS
-------------------------

1.      Identify top performing Games and highlight key factors contributing to their success.

2.      Present key market trends, top geographic and platform Popularity.

3.      Provide recommendations for stakeholders based on the analysis.


## OVERVIEW OF THE DATASET
-----------------------

The dataset was a comma separated value file, file size of 1.32 MB (1,389,095 bytes). The dataset was distributed by the organizers of the analytics corper workshop as final report challenge.

**Columns Profile**

There 12 columns in the dataset which are Rank Name Platorm Year Genre Publisher NA\_Sales EU\_Sales JP\_Sales Other\_Sales Global Sales.

The analyst made use of Microsoft Excel (Version 2310) to view the dataset and explore some insights about data structures of the file. Also, the data dictionary was not provided, so the analyst has to use personal intuition and judgement to find meaning to column names.

Based on the research of the analyst, the dataset provided appears to represent information related to video game sales. Here are the related meanings for each column:

         **Rank:** This column depicts the serial NO of video game based on data entry.

         **Name:** This column represents the names of the video games.

         **Platform:** This represents the gaming console or device on which the game user are using to play the game

         **Year:** Year of release of the Game

         **Genre:** This specifies the category of the video game. E.g Action, Football, Wrestling etc.

         **Publisher:** This represents the name of the company or entity that released, published or made the game.

         **NA\_Sales:** This column likely represents the sales of video games in North America (NA).

         **EU\_Sales:** This column likely represents the sales of video games in Europe (EU).

         **JP\_Sales:** This column likely represents the sales of the video game in Japan (JP).

         **Other\_Sales:** This column typically represents sales of the video game in regions other than North America, Europe, and Japan.

         **Global Sales:** This column represents the total global sales of video games.


# METHODOLOGY
-----------

This project is divided into three sections which are: Data Ingestion and Cleaning, Data Analysis and Visualization, Conclusion and Recommendation.

### Data Ingestion and Cleaning
---------------------------

The data source for this dataset is on the analyst's own computer, and the file size is 1.32 megabytes (MB).

The data was cleaned the data using Power Query Editor in Power BI Desktop version 2.121.903.0. Tasks such as organizing the data, changing column names, sorting, getting rid of empty columns, fixing missing values, trimming text, and making sure data types are correct. Our goal was to prepare the dataset for analysis, and we successfully achieved a 100% data quality for our columns.

![Power Query Image](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/Power_query.png)

After performing this task the data was loaded into power BI for further analysis.

**Data Analysis and Visualization**

Data visualization is like using pictures or graphs to help explain what we find when we analyze data. The analyst uses DAX (Data Analysis Expressions) to create special measurements that give us specific information. This makes our reports work faster, and it helps us focus on parts of the data.

**Top 5 Selling Console**

The analysis results showed that among all five gaming consoles, the total sales varied from $821,460 to $1,255,770. The top-selling console was the Playstation 2, generating $1.26 million in revenue from the sale of 2156 units. It was followed by the Xbox 360, which earned $979,600 million in revenue from 1264 units sold. The Playstation 3 ($957,890), the Wii ($926,050), and the Nintendo DS collectively brought in $821,460. billion in revenue, with the highest number of console units distributed (2162 units). This was mainly because this console had a low price per unit, resulting in a ratio of $380 per console. Playstation 2 accounted for 25.42% of the total sales. The Xbox 360 had the highest Price Per Unit to console ratio ($775), making it the most profitable console in the industry.

![A table with numbers and text
Description automatically generated](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/top_selling%20console_excel_calc.png)

![Top Selling Console](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/top_selling%20console.png)

**Total Revenue by Region**
North America had the highest total sales, reaching $3,298,690, followed by Europe, Japan, and other regions. North America's share of the total sales was 48.35%.

![Region Revenue](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/region_revenue.png)

**Top Selling Genre**

In this table, we can see the total sales figures for various video game genres. Action games stand out as the most lucrative genre, with total sales amounting to $1,750,160, indicating their strong popularity and financial success. Sports games follow closely behind with $1,330,540 in sales, showcasing their significant market presence. Shooter games come in third place with total sales of $1,036,840, emphasizing their popularity and profitability. Role-playing games secured the fourth position, generating $927,260 in sales, while platform games, with total sales of $831,040, claimed the fifth spot. This data provides valuable insights into the relative performance of these game genres, with action, sports, and shooter games dominating in terms of total revenue, making them attractive choices for game developers and publishers.

![Top Selling Genre](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/genre.png)

**Sales Trend**

![](challenge_report_files/image012.gif)

The table presents a historical overview of video game industry sales from 1980 to 2020. It shows the total sales figures for each year and calculates the percent change from the previous year where applicable. The data reveals significant fluctuations in the industry's performance over time. Notably, the industry experienced substantial growth in the early years, with a remarkable 213.53% increase in 1981 and 199.70% growth in 1984. However, there were periods of decline, such as a 41.83% drop in 1983 and a 73.08% decrease in 2016. In recent years, there have been sharp declines, including a 99.93% drop in 2017 and 100.00% in 2018, highlighting a considerable downturn. The industry showed signs of recovery with $290 in total sales in 2020. This data underscores the cyclic nature of the video game market, marked by both booms and contractions over the years.

**Top Selling Video Game**

![Sales Trend](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/sales_percent.png)**

The table displays the total sales figures for some popular video games. "Wii Sports" leads with the highest total sales of $82,740, making it the top-selling game in the list. "Grand Theft Auto V" follows with total sales of $55,920, demonstrating its significant popularity. "Super Mario Bros." comes next with $45,310 in total sales, highlighting the enduring appeal of this classic game. "Tetris" has total sales of $35,840, and "Mario Kart Wii" is nearly on par with total sales of $35,830. These numbers reflect the financial success and popularity of these games in the gaming industry. Based on the dataset there are 11 thousand distinct games in the industry.

**Top Earning Publisher**

**![Publisher Earninngs](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/publisher.png)**

The table presents the total sales figures for video game publishers. "Nintendo" leads the list with the highest total sales of $1,786,360, indicating their strong presence and success in the gaming industry. "Electronic Arts" follows closely behind with total sales of $1,110,150, showcasing their significant market share and revenue. "Activision" secures the third position with total sales of $727,110, demonstrating their substantial presence in the industry. "Sony Computer Entertainment" has total sales of $607,490, while "Ubisoft" is also a notable player with total sales of $474,510. These figures underscore the financial success and market influence of these major publishers in the video game industry.

**Additional Information**

![](https://github.com/Ainaganiu/Game-Industry-Analysis-Power/blob/main/Picture/second%20page.png)

From the analysis above, analysis of the line chart revealed consistent pattern where an increase in total transactions is associated with a rise in sales. To delve deeper into this relationship, we created a scatter plot. This plot clearly illustrates a positive correlation between the total transactions carried out by gamers and the total revenue generated. In conclusion, all other factors being equal, the data suggests that as the number of transactions increases, so does the overall sales or revenue. This finding emphasizes the significance of transaction volume in driving sales in the gaming industry.

**Recommendations**

Based on the analysis findings, it is recommended that high marketing efforts should be directed towards products with a high price per unit, such as the Playstation 2 Console. These products are more profitable and cater to a high-class consumer base. However, it's important to consider other associated costs, including shipping and production costs, when making marketing decisions. This approach ensures that marketing investments are directed towards products with the potential for the greatest overall profitability, taking both revenue and cost factors into account.

Another key recommendation is to allocate high investments to encourage game publishers to develop and publish games in genres that have the potential for high earnings. Diversifying the game genres can attract a broader audience, and capturing a wider range of gaming preferences can lead to increased sales and revenue. By incentivizing publishers to explore various genres and create high-earning games in those categories, the industry can tap into new market segments and maximize its overall reach and profitability.

Furthermore, more market concentration should be focused on the region with low revenue and strategies should be develop to continue this to drive sustainable profits and Relationship does not cause Causation.

## Report Link

For Power BI live report [Click Here](https://shorturl.at/gisvC)
