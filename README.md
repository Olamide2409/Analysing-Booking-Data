# Analysing-Booking-Data
# INTRODUCTION
The Hospitality Booking Data Repository Documentation gives a detailed and organized record of essential information related to hospitality bookings. This documentation acts as a crucial resource for stakeholders engaged in data-driven decision-making processes. Task involves a thorough analysis of a comprehensive dataset, featuring intricate details of bookings, guest demographics, distribution channels, and financial metrics. By applying your analytical prowess,aim is to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of the hospitality group in delivering unparalleled hospitality.
# TOOLS
Microsoft Excel
Microsoft PowerBi
# PROCESS
DATA WRANGLING AND DATA CLEANING
Open data into Microsoft Excel to inspect and save
Open Microsoft PowerBi
Click import data from excel and click transform data
Load a powerquery editor
Check each column for consistency and choose the appropriate data type for the respective column
For the booking date/arrival date column, choose the split column from the transform ribbon to split the column into day, month and year
Choose the custom option and input '/', choose split at "Each occurrence of the delimiter" and click Ok.
Save changes in the Powereditor query.
Click on the report view to start generating reports to address each objective of the analysis.

# OBJECTIVES
Booking Patterns:
What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity?
How does lead time vary across different booking channels, and is there a correlation between lead time and customer type?

Customer Behavior Analysis:
Which distribution channels contribute the most to bookings, and how does the average daily rate (ADR) differ across these channels?
Can we identify any patterns in the distribution of guests based on their country of origin, and how does this impact revenue?

Cancellation Analysis:
What factors are most strongly correlated with cancellations, and can we predict potential cancellations based on certain variables?
How does the revenue loss from cancellations compare across different customer segments and distribution channels?

Revenue Optimization:
What is the overall revenue trend, and are there specific customer segments or countries contributing significantly to revenue?
Can we identify optimal pricing strategies based on the Average Daily Rate (ADR) for different customer types and distribution channels?
Geographical Analysis:
How does the distribution of guests vary across different countries, and are there specific countries that should be targeted for marketing efforts?
Is there a correlation between the country of origin and the likelihood of cancellations or extended stays?

Operational Efficiency:
What is the average length of stay for guests, and how does it differ based on booking channels or customer types?
Are there patterns in check-out dates that can inform staffing and resource allocation strategies?

Impact of Deposit Types:
How does the presence or absence of a deposit impact the likelihood of cancellations and revenue generation?
Can we identify any patterns in the use of deposit types across different customer segments?

Analysis of Corporate Bookings:
What is the proportion of corporate bookings, and how does their Average Daily Rate (ADR) compare to other customer types?
Are there specific trends or patterns related to corporate bookings that can inform business strategies?

Time-to-Event Analysis:
How does the time between booking and arrival date (lead time) affect revenue and the likelihood of cancellations?
Are there specific lead time ranges that are associated with higher customer satisfaction or revenue?

Comparison of Online and Offline Travel Agents:
What is the revenue contribution of online travel agents compared to offline travel agents?
How do cancellation rates and revenue vary between bookings made through online and offline travel agents?

# DATA VISUALIZATION
Among various distribution channels, online travel agents exhibit the highest number of bookings and command the highest average daily rate, while undefined channels register the least activity. Moreover, reservations facilitated through online travel agents boast the longest duration of time spent, closely trailed by those made through offline travel agents. Notably, there is marginal divergence in the time spent on bookings between both direct and corporate channels. The peak period for bookings occurs in the initial two months(January, February) of the year, with a noticeable decline in reservations as the summer season commences, particularly in June
![Data VIisualization I](https://github.com/Olamide2409/Analysing-Booking-Data/assets/147916748/75991dfb-b178-466a-bea5-098cc4096f11)
Among customer types, transient customers experience the highest rate of cancellations, with transient-party following closely behind, and group customers having the least cancellations. Regarding revenue distribution, the deposit type associated with the greatest number of bookings and the highest generated revenue is 'No Deposit,' while the 'refundable' deposit type demonstrates the lowest revenue means
![Data Visualization II](https://github.com/Olamide2409/Analysing-Booking-Data/assets/147916748/99841fba-ae20-4c9a-a188-901325012de8)
The 'contract' customer type exhibited the longest average stay at the hotel. Among three distinct customer types, the 'refundable' deposit type boasted the highest average stay, except for the 'group' customer type, where the 'No Deposit' option recorded the highest duration.
Among the countries, Portugal, the UK, France, Spain, and Germany stand out with the largest number of guests and contribute significantly to the highest revenue generation.
![Data Visualization III](https://github.com/Olamide2409/Analysing-Booking-Data/assets/147916748/284a09ff-ee88-498b-90ca-d361168c9932)

# ACTIONABLE INSIGHTS TO IMPROVE FUNCTIONALITY
1.  Provide customized recommendations, exclusive offers, and personalized content to enhance the overall visitor experience.
2.  Assess the performance of marketing channels. The most effective channels for reaching and engaging potential visitors. Allocate resources more efficiently by
    focusing on channels that yield the best results.
3.  Develop targeted promotions and events during peak times(January, February) to capitalize on increased interest. Likewise, consider special promotions during off-peak seasons to          attract visitors during quieter periods.
4.  Explore partnerships with local businesses, travel agencies, or influencers. Collaborative efforts can expand the reach and attract new audiences.
5.  Ensure accessibility to a diverse range of visitors, including those with different needs or preferences.


