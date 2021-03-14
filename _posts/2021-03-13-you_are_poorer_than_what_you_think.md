---
layout: post
title: You are poorer than what you think
subtitle: Inflation is when you pay fifteen dollars for the ten-dollar haircut you used to get for five dollars when you had hair. — Sam Ewing
tags: [inflation, economy]
comments: true
---

I am a Mathematician & Engineer by training and a Data Scientist in practice. What does a Data Scientist do? Put it simply, a Data Scientist blends Mathematics, Statistics, Computer Science and Subject matter experience to make sense of data. The role varies by industry, but the final goal of such a role is to help with a data-driven decision making. The funny thing is that I got into it accidentally. I leave the story of how I got into it for later.

I have been digging into different datasets as part of my day job and also my side projects for a long time. Since pandemic I have got interested in datasets related to economy. In general, how economy works (10,000 feet view), how money works, how Federal Reserve works, and many more "hows". I spent 2020 reading about these subjects and looking at specific data sets.

One **important** subject that is mostly known to people (and affect people's life to the great extend) is **inflation**. For those who are not familiar with inflation, the inflation rate is the percentage increase or decrease in prices during a specified period. Why is this quantity important? One line answer: high/low inflation can make or break an economy. For example, if inflation is really high, let's say 10% per year, it means the same goods you buy today will be 10% more expensive next year. So you **expect** to pay more for the same good next year. What you might think to do to overcome the inflation at least temporarily is buy many of those goods. Imagine others think the same way and they buy those goods too. The more demand (with a constant supply), the more the price of those goods. In other words, expectation of inflation itself create more inflation. Another example: if your wage does not go up with inflation, you become poorer and poorer as time goes by. There re many reasons why high inflation is not good.On the other hand, low inflation is not good (and negative inflation which Japan experienced is even worse). If you know the price of a good is going to stay the same or goes down, would you buy it now? Maybe you do maybe you do not. Usually low inflation results in low consumption. Low consumption creates other problem down the road.

For aforementioned reasons and many more, central banks try their best to **stabilize** price. In the US, Federal Reserve has two mandates:
0. Price stability
0. Maximum sustainable employment

You might ask "well these are great mandates, but how does Federal reserve achieve those?" The answer to such a question is lengthy. I will try to get into it in future. In a nutshell, Federal Reserve has many tools in its disposal to use to achieve such mandates. Keeping interest rate low, printing money, quantitate easing, etc. are some of the tools in its disposal. Of course some of these tools have/are abused through time. I will address those in future as well. Long story short, we have a entity in the U.S that is responsible to achieve above mandates by using some important **tools**.

You can only change what you measure? How does Federal reserve measure inflation? This is a difficult question to answer.
0. What goods should we take into consideration when we calculate the price change? 
0. What regions should be considered in our calculation? What time frame? 
0. The quality of life usually increases over time, how do we take that into account when we calculate the inflation? 

Simple questions are usually not straightforward. Thankfully, we have an organization in the U.S. to do answer (some) of these questions and to measure  just that. U.S. Bureau of Labor Statistics is responsible to take these questions (and many more) into account and to measure (and report) the inflation on a regular basis. U.S. Bureau of Labor Statistics uses CPI to measure inflation. The Consumer Price Index (CPI) is a measure of the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services. Indexes are available for the U.S. and various geographic areas.

{% include image.html url="/assets/img/cpi-u.png" description="Fig 1. CPI-I example" %}

Figure 1 shows the sample of what U.S. Bureau of Labor Statistics reports on a regular basis. For example, Food at home CPI was 243.110 in Jan 2020 and it is 252.107. The percentage change is about 3.7%. The Bureau then combine all the percentages (some sort of weighted average) to come up with one number. **That number is the inflation**. Wait, what?? I know, I know,... the devil is in details. Just bare with me to explain the flaws in these types of aggregation. 



#### There is a level of subjectivity

How does Bureau come up with the categories? For example, **food** is a broad category and representing it with 6, 7 sub categories introduce some level of subjectivity. Bureau uses different surveys, research etc. to create a basket of goods, but still there is some levels of subjectivity in the end of the day. 

#### Average might not be a good statistics

Average is prone to outlier and might not be a good statistics to use. due to variance in price of goods based on their characteristics, it is wise to look at other statistics such as Median, and percentiles. With average, the story is summarized in one word and one word is most often misleading. 

#### Whenever you aggregate, you scarify something

No matter how delicate Bureau carries out the calculation, the aggregation *could* be very misleading. For example, if people in the US mostly eat Beef and Beef has been weighted heavily in the calculation, the final number will be influenced by beef more than let's say chicken. Again, no matter how you weight the items, as soon as you aggregate the numbers, you are dealing with *average* inflation. If you eat chicken a lot, the number represented here might not reflect how much your wallet is affected by inflation. Another level of aggregation occurs among categories. For example, food and energy must be weighted somehow. If you are heavy energy user, but not much food (which I do not recommend), the number reflected here might not be applicable to you.

#### Price depends on the region

Another flaw of these types of report is that the numbers are averaged among regions throughout the country. Sure, Bureau sub reports for each regions, but when the inflation is reported, it is only one number. This means that you might suffer from inflation heavily, and I might suffer from it mildly, but on average, the inflation is modest! 

#### Price depends on sub regions

Even when you look at one particular region, let's say Dallas metroplex (DFW), there are so much variance within DFW. For example, there are pockets of neighborhoods that might be affected heavily by inflation and other pockets not much, but again when the number is reported the inflation is reported as **modest*.  

#### In times of shock, inflation increases 

Whenever some shocks such as 2008 meltdown, 2000 tech bobble, 2020 pandemic, etc. happens, Federal Reserve uses its **tools** to stimulate the growth. 


There are, of course, more issues with the way the numbers are reported and interpreted. But I guess you got my points here. The number that Federal Reserve is targeting (2% inflation, recently changed to *average* 2%) might not do any good to you. It has been averages/aggregated so much, it does not reflect **your** lifestyle and most importantly, it could be very misleading. As a matter of fact, if you are planning your retirement, planning to buy a house, planning to buy a car etc. you should **really think twice** before relying on the report.

{% include image.html url="/assets/img/zillow-home-price.png" description="Fig 2. US home prices since 2012" %}

Looking at figure 2, you will not see any number close to 2%, more close to 7%-9% yearly inflation. 

#### Bottom line

I analyzing data, looking at the data and most importantly using it to lead a data-driven decision making process. At the same time, I am extremely careful about the limitation of data and danger of letting it fool me. Inflation is real, Bureau is doing its best to capture **average** price movement. But you no one is exactly **average**. There are so much variance in prices based on regions, sub-regions, style of living and many more factors. Just remember that what you hear in the news is just *one number* stories that are told with one word are not complete! Until next time.