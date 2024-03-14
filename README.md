### Information Visualization of CPI Food & Beverage and its Demographics in Malaysia
| Name                          | Matric No     |
| -------------                 | ------------- |
| Siti Aisyah binti Ismail      | 2010912       |
| Nur Syafini binti Ismail      | 2018028       |
| Nur Amanina binti Mohd Nubli  | 2018028       |
| Nur Athirah binti Zaaba       | 2011156       |
| Joyce Irene A/P Anthony       | 2018028       |


## 1.0 Executive Summary
The topic that is chosen for this project is ‘The Food and Beverage Consumer Prices trends in different states of Malaysia from 2021 to 2023’. The three main objectives that are being highlighted in this project is to analyze the yearly growth rate of food and beverage consumer prices within the Malaysian states over the past three years (2021-2023), to identify which state is the most and least impacted by food and beverage consumer prices and to find the relationship between the population and the consumer purchasing power of food and beverage in the states of Malaysia. In Tableau, it highlights what is Consumer Price Index (CPI), how CPI reflects population, CPI Of food and beverage by region, CPI population by region, CPI vs Population and CPI trends. Below is a concise summary about the project based on the data collected.

Based on the key findings, CPI (Consumer Price Index) Selangor experienced the highest CPI, indicating that the cost of living and prices for goods and services, particularly food and beverages, were relatively higher in this region during the given period while Sabah had the lowest CPI, suggesting that the cost of living and price levels were comparatively lower in Sabah compared to other regions. In population, Selangor had the highest population, indicating that it is a densely populated region with a significant number of residents while Perlis had the lowest population, suggesting a less densely populated area. Lastly, Percentage Increase of CPI (2021-2023), the CPI increased by 4-6% during the period from 2021 to 2023. This percentage increase reflects a moderate level of inflation, indicating a general rise in the cost of living and prices for goods and services over the two-year span.

The findings suggest a correlation between the cost of living, population size, and inflation rates in different regions. Selangor, with both the highest CPI and population, may face higher living costs, potentially impacting a larger number of residents. On the other hand, Sabah, with the lowest CPI, may offer a relatively more affordable living environment. The percentage increase in CPI indicates a moderate level of inflation across the regions. Policymakers and stakeholders can use these findings to tailor economic and social policies to address the specific needs of each region, considering factors like living costs and population density. Tableau offers a variety of tools for creating various types of visualizations, such as charts, graphs, maps, and dashboards. We were able to select from a variety of visualization options to represent data most effectively and engagingly. Moreover, Tableau facilitates narrative storytelling by creating a collection of visuals that lead the audience through a story.


## 2.0 Introduction
This project is mainly about studying the Food and Beverage Consumer Prices trends in different states of Malaysia from 2021 to 2023. Based on the problem statement we gathered from here is that ‘’Malaysia faces a complex economic challenge characterized by fluctuations in consumer prices for food and beverages across its various states. These fluctuations impact the well-being and purchasing power of the population. Furthermore, there is a need to understand the disparities in the effects of these price changes among different economic sectors. To address this issue effectively, it is crucial to identify the most impacted states, assess the relationships between population size and consumer purchasing power, and analyze these dynamics within distinct economic sectors. Solving this problem is essential for informed policymaking, business strategies, and equitable economic development in Malaysia.’’ Therefore, the purpose of conducting this project is to discover in depth about the Food and Beverage Consumer Prices trends in different states of Malaysia  from 2021 to 2023 precisely based on the Consumer Price Index (CPI), how CPI reflects population, CPI Of food and beverage by region, CPI population by region, CPI vs Population and CPI trends.

As for the first significance of the project, it is about economic stability. Assess national economic stability and inflation. The data gathered may be used to inform the development of monetary and fiscal policies with the objective of maintaining price stability. Secondly, consumer welfare. Population and consumer purchasing power in food and drink expenses are major indicators of community well-being. It helps raise living standards by determining how much consumers are able to spend on basic necessities. And the third one is that food and beverage companies need insights into consumer price patterns at the state level in order to develop effective regional marketing, pricing, and distribution strategies. This research may be used by companies to enhance their business operations.

Tools and techniques used in Tableau are Tableau's "Show Me" feature that suggests visualizations based on selected data fields. Tableau's “Drag-and-Drop” interface enables us to create visualizations by adding fields to the rows and columns shelves. “Trend and Reference Lines”, we add trend lines and reference lines to the visualizations to help identify patterns, trends, and benchmarks in the data and “Dashboards”. Dashboards in Tableau allow us to combine multiple sheets and visualizations into a single interactive view.

## 3.0 Dataset Description
The data used in this project is the Consumer Price Index (CPI) provided by the Department of Statistics Malaysia (OpenDOSM) for different states of Malaysia from January 2021 to January 2023. In Malaysia, CPI measures the average changes in the general level of prices of consumer goods and services purchased by households. 

In addition to the CPI data, this project also utilizes the population of Malaysian citizens from OpenDOSM to gain a comprehensive understanding of the demographic studies. The data is used to relate the CPI and understand consumer behavior across different states. 


## 4.0 Data Analysis

# 4.1 Data Preprocessing
<img width="498" alt="Screenshot 2024-03-14 094712" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/82a68187-815b-4d86-9e25-13c6d2d241dd">

_Figure 4.1 Raw general CPI dataset_

<img width="248" alt="Screenshot 2024-03-14 094859" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/3527e210-13f8-4927-935d-1edc2c0beca2">

_Figure 4.2 Raw state-wise population dataset_

Above is the raw data of CPI and population taken for each state within Malaysia that will undergo meticulous preprocessing through Microsoft Excel. This process involved a systematic series of steps to make the data feasible and usable. Firstly, the data were cleaned of unnecessary spacing, changing the format to a table form. The data was then inspected for any missing values. Any blank cells were filtered and removed to avoid any potential disruptions. Redundancy was addressed by removing any duplicated data, to ensure data integrity. The next step involved standardizing inconsistent data using the ‘Format Cells’ option. To focus the analysis, the data was filtered specifically to relevant points, such as the category for food and beverages.  

# 4.2 Key Findings 
<img width="235" alt="Screenshot 2024-03-14 095146" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/68f9ee30-934d-4a9b-b652-e33d901e4534">

_Figure 4.3 Processed CPI data of food and beverage_


<img width="304" alt="Screenshot 2024-03-14 095238" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/316b6eea-8d28-46c8-85f3-8960c613e649">

_Figure 4.4 Processed state-wise population data_

Drawing from the comprehensive datasets above, there are significant parallels that emerged in the date and state data column. This facilitated the alignment of data from the years 2021 to 2023, which offers a coherent temporal context for subsequent analyses. As for state data, a pivotal enhancement involved a new region column, which specifies states into distinct geographical regions – central, north, south, east coast, Sabah and Sarawak. The allocation of states to specific regions contributes to a more refined and regionally contextualized dataset.

In this regional classification, Selangor, Negeri Sembilan, and the Federal Territories of Putrajaya and Kuala Lumpur were designated as part of the central region. The East Coast region consists of Terengganu, Pahang, and Kelantan. The North region featured Perlis, Kedah, Pulau Pinang, and Perak while the South region included Melaka and Johor. Sabah and Sarawak, along with the Federal Territory of Labuan, were seamlessly integrated into the Sabah and Sarawak region. This strategic region-based categorization sets the state for a more valuable analysis and enables exploration of CPI and population variations based on both state and region. 


## 5.0 Storyboarding and Design Choices

The application of Gestalt principles is essential to improving user understanding and engagement when creating a dashboard that visualises Consumer Price Index (CPI) data for food and beverage across states in Malaysia from 2021-2023. 

**Orange-brown hues colour scheme**
Visual cohesiveness is ensured by the regular use of orange-brown colours throughout various graphs, which is in line with the concepts of proximity and similarity. It simplifies interpretation by establishing a common visual language among related components, such as population numbers or CPI data. Furthermore, combinations of warm colours, such as orange and brown, are associated with comfort, nutrition, and stimulation of hunger; hence, their usage in the visual representation of food and beverage Consumer Price Index (CPI) data is acceptable. (Oliver Breeds, 2023)

**Graphs used**
1. Geo Map
States that are close to one another on the geo map encourage people to link nearby areas with one another and feel more connected. The orange-brown gradient colour scheme used to colour-code CPI numbers draws attention to variances and emphasises how close states with comparable cost of living are to one another.

2. Dual axis bar chart
Applying the concepts of closeness and similarity, the dual-axis bar chart's close-grouped bars make comparing population and CPI figures easier. Users can quickly identify bars that are represented in contrast of colours (yellow and brown).

3. Tree Map
According to population size, the states are grouped on the tree map in accordance with the concepts of proximity and similarity. Orange-brown hues are consistent, making it easy for users to recognise states with high population densities. With the larger blocks denoting states with larger populations, the tree map clearly establishes a figure-ground link. This graphic hierarchy facilitates information attention.

4. Line chart
The line graph highlights the interconnectedness of data points and illustrates how CPI patterns have persisted throughout time. From 2021 to 2023, users may follow the line to see how CPI values for food and drink change state by state.

Images and fonts
When images are carefully incorporated and various font sizes from the Tableau and Arial font families are strategically used, critical conclusions may be communicated more effectively. The use of two fonts—Arial for adaptable reading and Tableau for data visualisation—contributes to a polished and well-organised design. A distinct visual hierarchy is established by the use of different font sizes within this short collection, with larger letters emphasising important ideas and smaller fonts keeping supporting parts in balance. When used carefully, pictures act as visual anchors, providing context and speeding up the absorption of important information. 


## 6.0 Tableau Visualization 

There are a total of 7 dashboards included in the storyboard:
1. Cover page
2. What is CPI?
3. How does CPI reflect the population?
4. Brief description of the dataset
5. CPI of food and beverage
6. CPI and population
7. Conclusion


1. Cover page
The cover page serves as the visual introduction to the presentation, featuring a compelling image that sets the tone for the subsequent content. It creates an initial impact and sparks interest, prompting viewers to delve into the insights presented.
<img width="423" alt="Screenshot 2024-03-14 095533" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/3ba2706b-155b-447c-85aa-43af61b390c1">

_Figure 6.1 Cover Page_


2. What is CPI?
This section provides a clear explanation of CPI (Consumer Price Index) to ensure that viewers have a foundational understanding of the metric.
<img width="394" alt="Screenshot 2024-03-14 095814" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/e175aa6b-9e37-4984-8b9e-232a67861860">

_Figure 6.2 ‘What Is CPI?’ Dashboard_

3. How does CPI reflect the population?
Expanding on the relationship between CPI and population, this section explores how CPI values offer insights into the cost of living and consumption patterns across different states. 
<img width="423" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/32c7ad9f-06e9-4d92-8a52-7c6ed93e9fbf">

_Figure 6.3 ‘ How Does CPI Reflect Population?’ Dashboard_

4. Brief description of the dataset
This page offers a concise overview of the dataset used in the presentation. 
<img width="422" alt="Screenshot 2024-03-14 095957" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/8ef3bd80-7321-4837-b5f2-e8555dd9138a">

_Figure 6.4 ‘ Brief Description of Dataset’ Dashboard_

5. CPI of food and beverage
Focused on the primary topic, this section features a geo map displaying CPI values for food and beverages across states in Malaysia. The interactive map allows users to filter data by year, providing a dynamic exploration of regional CPI trends. Users are also able to click the numbers of CPI in the region on the table which then highlights the locations in the geo map.
<img width="427" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/4750290c-6a2a-4437-9dba-7ab2f0378bf4">

_Figure 6.6 CPI of food and beverage Dashboard_

<img width="425" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/35ad694f-9cf7-4dcb-8aa8-cb006659672e">

_Figure 6.7 shows when Central Region is highlighted_

6. CPI and population
This page integrates a dual-axis bar chart illustrating the correlation between population and CPI values, a tree map visualising population distribution, and a line chart depicting CPI trends over the three years. The combination of these visuals offers a holistic view of the interplay between CPI and population. Users are able to filter by years and the selected data from each graph will reflect on the other graphs.
<img width="425" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/59923b29-34e9-4247-88a9-ab51ef35e1ed">

_Figure 6.8 CPI and Population Dashboard_

<img width="424" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/83e389dc-f233-411d-82ef-9fc2a6e29a6b">

_Figure 6.9 shows a population from Selangor is highlighted_

7. Conclusion
The conclusion page encapsulates the key findings and takeaways from the analysis. It includes a summary of the presentation, highlights the highest and lowest CPI values, identifies regions with the highest and lowest populations, and concludes with actionable recommendations. Images further enhance the impact and memorability of the conclusions drawn from the data.

<img width="430" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/93c16931-f6b8-4431-8a1c-b54f3f8057fd">

## 7.0 Data Storytelling 

To meet the objectives of this project, we created two interactive dashboards with the dataset that allow the viewers to get findings easily. 

The first dashboard that contains Geomap visualization together with a dataset of CPI for every region and state was created to inform the viewers on CPI on Food and Beverage for each state and region. This dashboard visualization will help the user identify the states with the highest and lowest values of CPI easily with the help of a heatmap geo map. This visualization also was created to meet the second objective of this project which is to find the states that were impacted by the CPI the most and least.

The second dashboard was created to inform the viewers of our first and third objectives which are to analyze the yearly growth of CPI within Malaysia states and to find the relationship between CPI and populations. The visualization contains three types of charts that were connected. The first one is the line chart to inform the viewers of the trend of CPI across states in Malaysia from 2021-2023 which is our first objective. To help the viewers understand our second objective, we create the bar chart with a dual axis which is CPI and populations of regions. This chart is also linked together with the treemap chart that displays the populations of each state. When one of the charts is clicked, the other chart will also change accordingly. This interaction will help the user to analyze the relationship between the CPI and populations easily and finally meet our third objective.
	

## 8.0 Results and Discussion 

<img width="426" alt="image" src="https://github.com/esahxkesah/cpifoodbeveragemyvisualization/assets/68623558/22cc4338-7ba2-448c-8286-226bfc8989e7">

_Figure 8.1 CPI Trend over 2021-2023 line chart_

Yearly growth rate of food and beverage consumer prices within the Malaysian states over the past three years (2021-2023).

The CPI increased by 4-6% during the period from 2021 to 2023. This percentage increase reflects a moderate level of inflation, indicating a general rise in the cost of living and prices for goods and services over the two years.

States with the most and least impacted by food and beverage consumer prices.

From the findings, we found out that Selangor is the state that experienced the highest CPI for food and beverages while Sabah had the lowest CPI within Malaysia, suggesting that the cost of living and price levels were comparatively lower in Sabah compared to other regions. On the other hand, Kelantan experienced the lowest CPI among states within the Peninsula.

Relationship between the population and the consumer purchasing power of food and beverage in the states of Malaysia.

Selangor had the highest population within Malaysia, indicating that it is a densely populated region with a significant number of residents while Perlis had the lowest population, suggesting a less densely populated area. 

Selangor experienced the highest CPI with the highest population hence it can be said that population does affect CPI within states however, it also can be influenced by other factors like market competition, labour costs, consumer preferences and demand, and many more.

## 9.0 Challenges and Limitations

Collaborative Editing Limitations:
Due to Tableau limitations, simultaneous editing of the dashboard by all group members was not possible. Compiling individual worksheets into the final dashboard became time-consuming since each group member had to send over their file to the person who would combine the worksheets into the dashboard. 

Impact: 
The collaborative editing constraint increased the time needed to complete the dashboard. It delayed project completion and reduced overall group efficiency.

Data Filtering:
The raw data is unclean, which includes unnecessary or unrelated information that needs to be removed in order to focus entirely on the Consumer Price Index (CPI) for food and beverages.

Impact:
Cleaning the data to match the scope increases the complexity. The possibility of accidentally changing important details during the cleaning process may have an impact on the accuracy of the final analysis and visualizations. As a result, cleaning the data takes a long time since data integrity is so crucial



## 10.0 Conclusion

In conclusion, analysis of the patterns in consumer prices for food and beverages across the states of Malaysia from 2021 to 2023 yields a number of significant insights. The data utilized in this study was obtained from the Consumer Price Index (CPI) of the Department of Statistics Malaysia. The CPI for the specified period exhibited a moderate 4-6% overall increase. Selangor, as the state, exhibits the highest Consumer Price Index (CPI), which signifies a relatively elevated standard of living and increased pricing for goods and services, particularly within the food and beverage sector. Conversely, Sabah exhibits the lowest CPI, implying a marginally more affordable quality of life. Additionally, the data indicates that Perlis is the least populous region, implying a lower population density, whereas Selangor is the most populous, signifying a densely populated area. The complex interplay between population size, CPI figures, and the moderate inflation rate underscores the considerable diversity in economic dynamics observed in different geographic regions. This data may be utilized by policymakers, businesses, and other stakeholders to assist them in tailoring strategies to the diverse economic conditions, population densities, and cost of living of Malaysia's several states.


## 11.0 Recommendations

Market Competition
- Use complex statistical models, like economic models, to figure out how market competition affects inflation rates over both short-term and long-term effects.
- Create interactive dashboards that show the relationship between market competitiveness and inflation over time. This might include interactive displays with customizable time spans that help policymakers discover patterns and trends.
Subsidies 
- Do an in-depth analysis of subsidies to find those that benefit certain industries or areas the most. 
- Use predictive modeling to forecast the future effect of subsidy changes on consumer prices, allowing for more proactive planning.
- Enhance data visualization by creating heatmaps to show how energy subsidies are distributed geographically and their economic effect on various locations.
Consumer Awareness
- Conduct a sentiment analysis on social media platforms to gather public opinion on food and beverage costs. Assess sentiment patterns and discover consumer awareness influencers.
- Use machine learning algorithms to find consumer awareness data patterns for more accurate trend forecasts.
- Integrate interactive components, including sentiment trend charts and word clouds, to present fluctuations in consumer awareness in a visually captivating manner.



## References

1. Competition and inflation - OECD. https://www.oecd.org/daf/competition/competition-and-inflation.htm
HLG-MOS workshop on the modernisation of Official Statistics - UNECE. https://unece.org/sites/default/files/2023-12/HLG2023%20Report.pdf

2. Oliver Breeds (2023), Best food colours for marketing
https://adflex.io/blog/best-colors-for-food-marketing/

3. THE COMPILATION OF CONSUMER PRICE INDEX IN MALAYSIA
https://sesricdiag.blob.core.windows.net/oicstatcom/BIG_DATA_Compilation_of_CPI_in_Malaysia_EN.pdf

4. MALAYSIA'S OFFICIAL OPEN DATA PORTAL
https://open.dosm.gov.my/data-catalogue










