# SURFS_UP Data Analysis with SQL & Flask
BootCamp Data Analysis Week9: 

# Overview
Previuosly, we made a Weather Analysis in the province of O'ahu, Hawaii,  with the purpose of showing projections to future prospects willing to invest in a small ice cream and surf equipment rental bussiness. We deliviered the analysis of all around one year an now, they have asked us to repeat the projections specifically of the temperature history for the months of June and December. Again we will take the data stored in a SQL database to be able to show it to future business partners.

# Results:
We started from the database of temperatures hawaaii.sqlite and realized queries to find the June and December temperatures, we stored in pandas DataFrame and display their stats. Later I compared with the historical temperature histogram from the previuos analysis.



## Temperature  Queries and DF Stats

**Historical June** 

<img width="926" alt="June Query" src="https://user-images.githubusercontent.com/102195803/172018735-6ef7dd27-0687-43a9-90d9-85e7f0eef87f.png">

<img width="343" alt="June_Temp_Stats" src="https://user-images.githubusercontent.com/102195803/171972480-62ff4c03-9bc1-443d-8401-812fdb87c717.png">

**Historical December**

<img width="969" alt="December Query" src="https://user-images.githubusercontent.com/102195803/172018749-a6c643cd-b50a-42e5-bed3-0665e35b0c1e.png">


<img width="343" alt="December_Temp_Stats" src="https://user-images.githubusercontent.com/102195803/171972485-b9a44625-07c2-4653-b802-9e509abdb466.png">

**All Year Average temperatures (2016-2017)**

<img width="460" alt="All_Year_Average_Temp" src="https://user-images.githubusercontent.com/102195803/171972833-b247f50a-8ffb-41eb-8656-81f33a54a209.png">

## Results
From this stats, we can observe that:
  1. The average temperature in this months are between 71 and 74 °F, the year´s average temperarture.
  2. The maximum temperature is very similar in the  two months, 83 and 85 °F.
  3. The minimun temperature in December is 56 °F, maybe to cold for an ice cream!
   
# Summary
From the data collected, we can observe that both June and December are excellent months to visit O'ahu, taking advantage of the holidays! It should be considered that in December, temperatures decreases to 56° F, perhaps too cold to eat ice cream, but maybe the weather its suitable for surfing! I propose two additional queries that could give us more information about how convenient are these months: one that shows us the statistics of precipitation for each month, and taking precipitations filtering only by the most active  station in order to have more exact data.

