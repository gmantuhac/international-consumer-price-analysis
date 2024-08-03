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

![China](https://drive.google.com/file/d/1f07eTBCLcqrQpfrcM-LzdetgG76yHD2X/view?usp=sharing)
![Dominica](https://drive.google.com/file/d/1rxgmM9zYWf9bIi7q1C3cSCim-4MsKYZg/view?usp=sharing)
![Lithuania](https://drive.google.com/file/d/1r7PmHTZlhTrt-hnu36EaAup9dHA1ashu/view?usp=sharing)
![Switzerland](https://drive.google.com/file/d/18OMPDEQdf3VkXBiY7DtlA02ohDtpUoO2/view?usp=sharing)
![All Countries](https://drive.google.com/file/d/1dO1DhalK3nuvlYBIx0piDPiH0dQahtqP/view?usp=sharing)

In each plot, the y-axis represents the consumer price. The x-axis represents each month starting from 01/2000. So 2 on the x-axis represents 03/2000. The first plotted line represents each the line created after using each consumer price data point. The red line represents the general trend for the first plotted line. Based on the data and plots given, it seems like each country **does not** grow at a relatively similar rate. For example, Switzerland, compared to other countries, tends to barely grow at all compared to the other countries. Is this due to geography (which I am leaning towards) or politics? Switzerland is also known to generally be a really expensive country. I am curious. Another example is Lithuania who, initially seems like the general trend grows similarily to China and Dominica, has an outlying spike in consumer price nearing 2022. Did Lituania have a huge spike in inflation? Or a somesort crash in the economy? Very curious. 

I can therefore confidently say that my hypothesis was **incorrect**. While multiple countries may grow at a similar rate from each other, as seen for China and Dominica, the internal issues within a county greatly dictates their food consumer price points.

Again, this is another relatively simple project. However, I am very proud of myself. I am on the path towards a career that actually interests me. Very excited for what the future lies ahead.

As a statement for myself: *I am a strong individual and will overcome hurdles to build a good future for myself.*
