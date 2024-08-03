# International Food Consumer Price Data Analysis

This project serves as a simple data analysis on food consumer price trends from 2000 to 2022 using 4 randomly selected countries. I decided to use the data due to my casual lifelong interest in countries themselves. The four countries I used were China, Dominica, Lithuania, and Switzerland. These countries were chosen using a randomized country [generator](https://random.country/). I used this method because it is similar to getting a random sample.

Here are the data sets I retrieved for each country:
- [AmeriGEO Food Consumer Price Data Set for **China**](https://data.amerigeoss.org/dataset/faostat-prices-for-china)
- [AmeriGEO Food Consumer Price Data Set for **Dominica**](https://data.amerigeoss.org/dataset/faostat-prices-for-dominica)
- [AmeriGEO Food Consumer Price Data Set for **Lithuania**](https://data.amerigeoss.org/dataset/faostat-prices-for-lithuania)
- [AmeriGEO Food Consumer Price Data Set for **Switzerland**](https://data.amerigeoss.org/dataset/faostat-prices-for-switzerland) 

This project serves to answer the question: **Do all countries' consumer prices grow at a relatively similar rate from each other?** The purpose of the creation of this question is pure curiosity. My hypothesis was that *all countries' relatively grow at a similar rate because many extremely important resources (ex: grains) are dependant in every country and therefore control a huge portion of the global market.*

The purpose of doing this project was to gain a proficient understanding in:
- Data cleaning using SQL
  -  Dropping unnecessary columns
  -  Organizing rows using constraints
  -  Checking for unnecessary Null-values
- Using packages in Python
  - mysql, numpy, maplotlib
- Bivariate exploratory data analysis

I created a [Google Doc](https://docs.google.com/document/d/197OT6UtGHxVGGiH3_0AEhvGZ4uQXju0cs5PN_qDE04E/edit?usp=sharing) that shares my experience everyday during the process of this project. This doc shows a raw experience of my processes and difficulties during the extent of this project. Each day, when worked on this project, was about an average of two hours. In my last project, I mentioned that I wanted to be more productive for future projects. That was not achieved in this project; however, I still aspire and strive to improve myself with each pressing step.

![China](https://cdn.discordapp.com/attachments/938667785679147030/1154188809072807966/wdQjccOcvYAKAAAAABJRU5ErkJggg.png)
![Dominica](https://cdn.discordapp.com/attachments/938667785679147030/1154188886331899914/IDXr18jOzvboT9aqNFo8NNPP6G6uhparRYzZ86EyWRyHWJyDlU0vEhOBEREZEb4j07RERE5NbY7BAREZFbY7NDREREbo3NDhEREbk1NjtERETk1tjsEBERkVtjs0NERERujc0OERERuTU2O0REROTW2OwQERGRW2OzQ0RERG6NzQ4RERG5tX8AFSAkukvSQ34AAAAASUVORK5CYII.png)
![Lithuania](https://cdn.discordapp.com/attachments/938667785679147030/1154188911380267028/sEBERkVdjsUNERERejcUOEREReTUWO0REROTVWOwQERGRV2OxQ0RERF6NxQ4RERF5NRY7RERE5NVY7BAREZFXY7FDREREXo3FDhEREXk1FjtERETk1f4BM81YZGrZtkYAAAAASUVORK5CYII.png)
![Switzerland](https://cdn.discordapp.com/attachments/938667785679147030/1154188969299427349/ljFkd7mmhjUAAAAASUVORK5CYII.png)
![All Countries](https://cdn.discordapp.com/attachments/938667785679147030/1154188999729094666/cY9OnT6ewsJC77rqLw4cP07lzZ5YtW0b9vXdvv6gQYNYuHAhV199NYcOHWLOnDluTT4WFhbGhAkT2LVrF7Vr16Znz54sWLDA7dcVEd9RuSEV4TBFDZ0iIiIiAUh9dkRERCSgKdkRERGRgKZkR0RERAKakh0REREJaEp2REREJKAp2REREZGApmRHREREApqSHREREQloSnZEREQkoCnZERERkYCmZEdEREQC2v8HkNKNhgxYbDIAAAAASUVORK5CYII.png)

In each plot, the y-axis represents the consumer price. The x-axis represents each month starting from 01/2000. So 2 on the x-axis represents 03/2000. The first plotted line represents each the line created after using each consumer price data point. The red line represents the general trend for the first plotted line. Based on the data and plots given, it seems like each country **does not** grow at a relatively similar rate. For example, Switzerland, compared to other countries, tends to barely grow at all compared to the other countries. Is this due to geography (which I am leaning towards) or politics? Switzerland is also known to generally be a really expensive country. I am curious. Another example is Lithuania who, initially seems like the general trend grows similarily to China and Dominica, has an outlying spike in consumer price nearing 2022. Did Lituania have a huge spike in inflation? Or a somesort crash in the economy? Very curious. 

I can therefore confidently say that my hypothesis was **incorrect**. While multiple countries may grow at a similar rate from each other, as seen for China and Dominica, the internal issues within a county greatly dictates their food consumer price points.

Again, this is another relatively simple project. However, I am very proud of myself. I am on the path towards a career that actually interests me. Very excited for what the future lies ahead.

As a statement for myself: *I am a strong individual and will overcome hurdles to build a good future for myself.*
