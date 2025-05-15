# Amazon Delivery Operations

This dataset is from Kaggle and it has 43,000 rows. This dataset only contains the delivery operations of 2022, including 3 months which are Feb, March and April. 

## Objective:
The primary goal of this analysis is to evaluate delivery efficiency, assess agent performance, identify operational bottlenecks (geographical and time-based), and improve resource allocation and planning strategies.

## Key Insights & Observations

Since we didn't have a delivery date column, we assumed that the delivery date was the same as the order date. Additionally, the fact that the delivery time was recorded in minutes supports the assumption that it was delivered on the same day.

Pickup delay is highest during midnight possibly because of less number of agents, staff shortage during midnight.

During the month of March, the dataset recorded the highest number of orders in the observed period. Despite this, the number of products ordered from each category remained consistent, indicating:
- Stable demand patterns across product categories
- No product shortages or inventory pressure during peak order cycles

Since the pickup delays remain constant it suggests that there are no operational bottlenecks which is a good sign. This did not affect the agent's performance either. The average agent performance is consistently high at around 4 out of 5.

During the month of March the orders were mostly from:
- Jaipur, India
- Indore, India
- Vadodara, India
- Gujarat, India
- Pune, India
- Mumbai, India
- Hyderabad, India
- Bangalore, India
- Coimbatore, India

This suggests that we should focus on improving the operations of these regions more to help satisfy customers.

There is an equal demand for products from all the categories which can help us in inventory planning. We can run targeted campaigns to influence category preference. 

During peak traffic hours, especially around 3:00 PM, there is a noticeable spike in pickup delays which means that the operational planning (like delivery slot allocation or agent dispatching) may benefit from traffic-aware scheduling. Thus, it can help reduce the pickup delay.

## How does it impact the business?
- Identifying the time-based delays which helped in reallocation resources and adjust staff patterns, especially during peak hours.
- High delay time slots and high volume regions can ensure faster delivery serves which helps in boosting customer satisfaction.
- Due to this analysis, I figured out that we have a stable product category which helps in inventory planning and this reduces overstock risks which prevents the company from spending the money on something that's not needed.
- The balance in all the product categories helps in planning and strategizing marketing ideas and maximize the product visibility.
- Evaluating agent ratings alongside the pickup delays allows the company to reward consistent performers but unfortunately this dataset doesn’t provide complete agent information.

## Conclusion
This analysis equips stakeholders with a clear, data-backed understanding of delivery operations. By acting on these insights, Amazon can:
- Reduce pickup delays
- Streamline delivery processes
- Improve regional performance
- Enhance overall customer experience
