# Final-Project-Tableau

## Project/Goals

#### 1. Employing Tableau to transform data into easily understandable visual representations.

#### 2. Crafting compelling dashboards that assist stakeholders in making informed decisions to tackle business inquiries and challenges.

#### 3. Conveying insights effectively through appropriate visualizations.


## Process

#### STEP 1

#### My dataset consists of a single Microsoft Excel Worksheet encompassing Airbnb information from New York City, comprising 13 columns and 30,478 rows of data.

#### In Step 1, I undertook the following actions:

#### 1. Imported the Excel file containing the dataset into Tableau. Given that there is only one table, there was no necessity to establish relationships or perform table joins.

#### 2. Conducted a dataset preview to discern the data types within each column and diligently noted cells with null values.

#### The identified data types encompass:

#### - 7 columns consisting of whole numbers.
#### - 4 columns containing string data.
#### - 1 column representing date information.
#### - 1 column containing geographic information.

#### STEP 2

#### I crafted visualizations to gain a comprehensive understanding of the data and the interrelationships among various variables. Here are some of the key findings:

#### - Property Count by Neighborhood: This chart unveiled the presence of 5 neighborhoods, namely Bronx, Brooklyn, Manhattan, Queens, and Staten Island. Remarkably, Manhattan possesses 52% of the properties available for Airbnb rentals.

#### - Count of Property Types: The dataset encompasses a total of 15 property types, with "Apartment" types accounting for approximately 89% of the listings.

#### - Revenue by Property Type: Among property types, "Apartment" properties contribute significantly to the revenue, comprising 88% of the total across all neighborhoods.

#### - Average Price by Room Type: There exist 3 room types - "entire home/apt," "private room," and shared room. Among these, "shared room" emerges as the most budget-friendly option.

#### - Map of Airbnb Locations: It's intriguing to note that some locations (ZIP Codes) extend beyond the boundaries of New York City, presenting an anomaly within the dataset.

#### - Price Over Time: Rental prices exhibited a consistent upward trend from June 2008, reaching their peak in January 2014. A 3-year forecast indicates a continued growth trajectory, but with a confidence band that is too wide, making predictioms ineffective. This suggests anomaly in dataset.

#### STEP 3

#### I formulated thought-provoking questions aimed at extracting insights from the available dataset. Here are the questions along with their corresponding answers from the charts:

#### 1. What types of rooms are rented the most?

   #### - Answers: 
              When considering the number of reviews, the most favored room type is "Home/apartment,"
              with a total of over 120,000 reviews. In terms of price, "Home/apartment" is also the
              preferred choice, boasting the highest average price of $295.

#### 2. Which neighborhood is the most popular?

   #### - Answers: 
                   In terms of the number of reviews, Manhattan emerges as the most preferred neighborhood,
                   amassing a total of over 120,000 reviews. When examining neighborhood names and addresses,
                   Queens stands out as the most favored, with a total of 324 reviews.

#### 3. Which neighborhood has the most listings?

   #### - Answers: 
                   When considering the number of listings, Queens takes the lead in terms of quantity.
                   Furthermore, when examining Host IDs, Queens remains the neighborhood with the most listings.

#### 4. Which property type generates the highest revenue?

   #### - Answers: 
                   Among property types, "Home/apartment" in the Manhattan neighborhood generates the most revenue.

#### 5. Are Manhattan hosts the highest rated?
   #### - Answer: 
                   Brooklyn hosts receive the highest ratings.


#### STEP 4

#### I created a dashboard that offers a comprehensive overview of the dataset's relationships and trends. Additionally, the dashboard incorporates charts that deliver responses to the questions I formulated.

#### STEP 5
#### I proceeded to construct a narrative based on my analysis, utilizing a variety of charts to convey key insights. Ultimately, I concluded by summarizing the analytical discoveries and offering recommendations for future investments in the thriving Airbnb business within New York City.


## Results

#### I opted for Airbnb listings in New York City (Option 2).

#### The visualizations I crafted, the questions I formulated, and the dataset's responses have been detailed in steps 2 and 3 as mentioned above. Here is a concise summary of my findings:

#### • There are 5 neighborhoods offering rental services.

#### • A total of 15 property types are available across these neighborhoods.

#### • The dataset spans from June 2008 to August 2015 in terms of timeline.

#### • Manhattan stands out with the highest number of properties and commands the highest prices.

#### • Brooklyn shines in terms of hosting quality.

#### • "Apartment" property type contributes a significant 88% of the total revenue across all neighborhoods.

#### • The Airbnb business demonstrates consistent growth trends in New York City.


## Challenges 

#### 1. I did not opt for option 1

#### 2.  Given my relative inexperience with Tableau, I required additional time to ensure that my charts effectively addressed the specific inquiries I had in mind.

#### 3.  I encountered some difficulty in determining whether utilizing the SUM, AVERAGE, or Count of numerical columns in my visualization charts would best align with the questions I aimed to answer. Through patient deliberation and logical reasoning, I was able to resolve this uncertainty.

## Future Goals

#### If I had additional time, I would:

#### 1. Dive deeper into exploring functionalities such as Parameters and Level of Details (LOD).

#### 2. Gather further insights into the dataset, carefully strategize, and execute the most effective approach to handle null values.

#### 3. Investigate anomalies in the dataset where ZIP Codes, ostensibly related to NYC, are appearing in Massachusetts, California, and Washington DC.
