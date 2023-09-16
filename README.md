# Final-Project-Tableau

## Project/Goals
The goal is to analyze Airbnb’s listings in NYC using various data visualization methods to uncover meaningful patterns and trends in the local market. The findings will offer value to prospective Airbnb investors seeking opportunities in NYC.

## Process
### Step 1:
Leveraged Python to explore and clean the data (e.g. remove duplicates/nulls, observe data types, etc.). Review the data cleaning and exploration process on airbnb.ipynb

### Step 2:
Imported the cleaned dataset into Tableau and explored it using a range of visualizations. The exploration process included:
* A map to visualize the distinct neighborhoods in NYC. 
  * **Finding**: Identified 5 zip codes that were outside of the state of New York. As a result, we excluded these discrepancies from the data.
* A heat map to pinpoint the areas with the highest concentration of listings. 
  * **Finding**: Manhattan has the highest concentration of listings among the 5 neighborhoods.
* A pie chart that calculated the percentage breakdown of Airbnb listings by neighborhood.
  * **Finding**: Almost 91% of the total listings in NYC are in Manhattan (52.68%) and Brooklyn (38.29%). While these two boroughs dominate the NYC market, there may be substantial growth opportunities waiting to be explored in the lesser-represented boroughs.
* A bar chart that calculated the percentage breakdown of Airbnb listings by room type in each neighborhood. 
  * **Finding**: With the exception of Manhattan, private room listings dominate the market in other boroughs. Potentially signally preferences of travelers or renters seeking more affordable and communal accommodation options.
* A box plot diagram to detect outliers in the average price in each neighborhood.
  * **Finding**: Identified two atypical data points in Brooklyn, priced at $1,500, and Queens, priced at $731. While these prices fell outside the typical range, they were considered plausible and were retained in the dataset. These anomalies suggest potential variations in the local housing market, possibly indicating emerging trends or unique property features in these areas that command higher or lower prices than the average.
    
Review the exact visualization in the repository's Tableau Workbook or in the Project’s Presentation.

### Step 3:
Constructed visualizations to explore specific inquiries within the dataset aiming to uncover trends that could be valuable for prospective Airbnb investors.
* Does the number of beds have an impact on the average price per night? **Finding**:
  * Beds doesn’t appear to have a significant impact on average price, as each room type has a similar average number of beds. The most significant factor influencing pricing appears to be the room type and the listing's location.
  * Increased privacy in accommodations consistently command higher listing prices as the average price for renting an entire home or apartment is more than twice the cost of private and shared rooms.
* Is there a relationship between average price and number of reviews? **Finding**: 
  * There doesn't appear to be a definitive relationship between average price and number of reviews. Tableau has organized the data into three prominent clusters, which seem to be grouped according to room type. This aligns with the logical assumption that room types with similar prices are clustered together, even though there isn't a direct correlation with the average number of reviews.
* How has the average price per night in each neighborhood changed over time? Include a forecast for the next two years. **Finding**: 
  * With the exception of the Bronx and Staten Island in 2012, the chart indicates that over time the price in each neighborhood haven’t been subject to drastic price fluctuations. The projected 2-year forecast emphasizes the same trend to continue.
  * The trend line for each neighborhood indicates a low R-squared and statistically insignificant p-values. Despite the less-than-ideal statistical results, it's worth noting that the relatively stable average prices and future outlook could be viewed as a positive sign for potential investors.
* How has the number of hosts in each neighborhood changed over time? Include a forecast for the next two years. **Finding**:
  * Over time, Manhattan, Brooklyn, and Queens have experienced consistent growth in the number of new Airbnb hosts, whereas the numbers have remained relatively unchanged in the Bronx and Staten Island. The 2-year projection highlights the expectation of this trend continuing. It's important to highlight that Queens is anticipated to witness remarkable growth of over 45% in the coming year, making it an intriguing prospective neighborhood for potential investors.
* Display the top 20 hosts by number of listings, are there patterns in the neighborhoods, room types and property types? **Finding**:
  * The majority of hosts concentrate their listings in 1-2 neighborhoods and between 1-2 property types. What's intriguing is that even though most of them have entire houses/apartments available, they often choose to list private or shared rooms. These charts also underscore the popularity of neighborhoods like Manhattan, Brooklyn, and Queens among hosts.
  * Recognizing current host preferences can provide valuable insights for investors as it enables them to either replicate successful strategies or identify untapped market opportunities.

## Results
Each visualization was created to uncover trends or patterns aimed at providing potential investors with valuable insights into the Airbnb market in NYC. The key insights were: 
* **Neighborhood and Host Growth**: Listings in Manhattan and Brooklyn dominate the NYC market therefore, we can assume a potential untapped market in the other boroughs. Investors should consider investing in neighborhoods like Queens, where host numbers are expected to grow significantly (45%+), based on a 2-year projection.
* **Price Trends Over Time**: Most NYC neighborhoods have experienced relatively stable average prices over time. The projected 2-year forecast suggested a continuation of this trend, offering a sense of market stability for potential investors.
  * The most significant factor affecting pricing is the room type and listing's location.  Increased privacy in accommodations consistently command higher listing prices as the average price for renting an entire home or apartment is more than twice the cost of private and shared rooms. Recognizing the impact of room types and locations can guide investors toward profitable opportunities.
* **Top Host Insights**: Most hosts focus on 1-2 neighborhoods and offer private or shared rooms despite having entire properties available. Given that approximately 95% of these top hosts share this approach, it underscores the viability of this business model.
  * For potential investors, this insight highlights the potential success of specializing in specific neighborhoods and prioritizing private/shared rooms listings, which could lead to increased booking rates and profitability. It reinforces the importance of a targeted and focused approach in a competitive Airbnb market.

## Challenges 
* Crafting questions that would extract the most valuable insights from the dataset.
* Selecting the appropriate visualization type to convey the intended message.

## Future Goals
* Find additional data sources that would enhance the level of detail in the dataset (e.g. bookings, cancellations, damage costs, etc.)
* Analyze alternative Airbnb markets and compare the patterns/trends.

