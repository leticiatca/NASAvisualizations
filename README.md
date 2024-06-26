## 🚀 NASA Visualization Case

This case looks at data from the failed NASA challenger launch and aims to propose solutions on how the data could have been better presented to avoid a disaster.

More visualizations and Interactive Dashboard: [Link](https://public.tableau.com/views/NASA_Dashboard_17119304651920/Story1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

## The Scenario
The launch of the Challenger space shuttle marked another important milestone in the story of space exploration and developments by NASA. However, the night before it was supposed to take place, engineers in the team of the rocket motor started to show concerns around the conditions of the launch. These engineers looked at data from all the tests and got to the key insight that the climate conditions, especially the temperatures, in the day of the desired launch were too low if compared to the ones of the successful tests. They had significant reason to believe that the O-ring component in the rocket would fail under the cold temperature. The business question then became if a delay of the launch due to the weather conditions concerns was worth the potential repercussions this would have on the mission and to NASA as an institution.

## The original visualizations
While the engineers were convinced that a delay would be the best option, the NASA officials that ultimately made the decisions were not convinced. The most important data to be considered here is the one that came from the test launches. This data was used by the engineers and presented through 7 exhibits. From these exhibits we can narrow down the ones that bring the information that is most important to the launch: Exhibit 2, recording the data from the tests and the precise information on the cases where erosion of the O-ring happened. Exhibit 5, recording the historical temperatures for the tests for all motors and other conditions. Exhibit 6 and 7, presenting the insights and concluding that the engineers gathered from this analysis. For both exhibit 2 and 5, the useful data that could have been used to convince NASA officials gets lost in the clutter of the charts. A lot of the information is highly technical and the main points get lost within other observations that are not essential for the purpose of the insight trying to be communicated. There is no visual aspect to make their point come across clearly. Many of the important points that are essential to interpret the data is lot in footnotes or can only be understood if multiple exhibits are read together. All these aspects make it hard for the engineers to emphasize just how crucial their finding is. Even if in Exhibits 6 and 7 the points are stated in a direct manner, the data to back up the statements is not being presented in a convincing way.

Original Exhibit 2
<img width="941" alt="Screenshot 2024-02-19 at 5 24 29 PM" src="https://github.com/leticiatca/NASAvisualizations/assets/84414010/ea6300a6-0ed0-4a04-9f7f-ec6c596cf67c">

Original Exhibit 5

<img width="621" alt="Screenshot 2024-02-19 at 5 26 50 PM" src="https://github.com/leticiatca/NASAvisualizations/assets/84414010/e838b2e5-5dbc-4f6e-b855-19297ddda50f">

## Analysis and Improvements
Placing myself in the shoes of the engineers trying to convey such an important message on such a complex scenario I believe there was room for improvement in the visualizations and data presented to the NASA officials. While the engineers had the technical knowledge, they failed into communicating their insights in an actionable way that conveyed the real significance of the issue they identified. To solve that, I would propose two main visualizations with the O-ring data that make the relationship between cold temperatures and failures more clear. 
In Exhibit 1 you can see a bar chart that shows on one side the historical data of the O-Ring temperature in the tests in a descending order, below you can see the corresponding erosion incidents for each test flight. This presents in a singular image how the most erosion incidents happened in the colder temperatures and highlights another key insight seen in the original exhibits that the coolest launch without failure happened at 66ºF. In Exhibit 2 we see another visualization that by itself should be enough to aid in decision making, it plots the trend line between O-ring incidents and temperature, showing how there is a clear relationship between the two variables. It also presents the mean and median values for the test launches and uses the 95% confidence interval of the data to assess the regions with bigger risk of failure based on the test data. It shows in an easy to digest way how the temperatures of the day for the launch was very much in a risky zone and all of the test flight data suggested that an of the O-ring would be likely. By presenting the information in fewer more compelling visualizations that focus on the important points to understand the key insight the engineers could have possible avoided a huge incident that cost lives.

Exhibit 1 – Bar Chart of O-Ring temperature and Erosion Incidents in each Test Flight!
<img width="1085" alt="Screenshot 2024-02-19 at 9 42 44 PM" src="https://github.com/leticiatca/NASAvisualizations/assets/84414010/cb1d712b-e271-409a-ba2a-404e0f8013be">


Exhibit 2 – Risk of O-Ring Erosion by Temperature (ºF)
<img width="1085" alt="Screenshot 2024-02-20 at 4 02 45 PM" src="https://github.com/leticiatca/NASAvisualizations/assets/84414010/db5ae2c2-265a-461f-b069-f102d590cb95">
