# airline_dataset
Flight Data Visualization and Analysis
Overview
This script analyzes and visualizes flight dataset features such as airlines, departure times, arrival times, source/destination cities, ticket prices, travel duration, and days left before departure.
It uses Matplotlib and Seaborn to generate various plots, helping to uncover trends and relationships between flight characteristics and ticket prices.


 Visualizations in the Script
1. Airline Frequency
Chart: Vertical bar chart

Insight: Shows the number of flights per airline.

Customization:

Dark blue bars

Dashed grid lines

Value labels above each bar

2. Departure & Arrival Time Distribution
Chart: Horizontal bar charts (side-by-side)

Insight: Compares frequency of different departure times and arrival times.

Customization:

Separate subplots for departure and arrival

Value labels inside/outside bars

Yellow color for arrival time bars

3. Source & Destination City Distribution
Chart: Pie charts

Insight: Shows the proportion of flights from each source city and to each destination city.

Customization:

Percentage labels with one decimal precision (%1.1f%%)

Two subplots in a single row

4. Average Ticket Price by Airline
Chart: Line plot with markers

Insight: Compares the mean ticket price across different airlines.

Customization:

Price values labeled above each point

Dashed grid lines for readability

5. Price vs Class per Airline
Chart: Grouped bar chart (Seaborn catplot)

Insight: Compares ticket prices for different classes within each airline.

6. Relation Between Stops & Duration by Airline
Chart: Scatter plot

Insight: Shows how travel duration varies with the number of stops for each airline.

7. Ticket Price by Departure & Arrival Time
Chart: Two line plots (one for departure time, one for arrival time)

Insight: Shows how average ticket price changes depending on flight timings.

8. Ticket Price vs Days Left Before Departure
Chart: Line plot

Insight: Shows how ticket prices vary depending on how many days before departure tickets are purchased.

 Key Insights
Identify the most popular airlines and flight timings

Understand price variations by airline, time of day, and booking period

Compare ticket prices between economy and business classes

Explore the relationship between stops and duration

Analyze city-to-city flight distribution
