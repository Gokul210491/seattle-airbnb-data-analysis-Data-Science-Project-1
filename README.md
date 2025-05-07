# 🏡 Seattle Airbnb Analysis: What Makes a Listing Expensive?
This project explores Airbnb listings.csv data for Seattle using Python, Pandas, and Seaborn. The analysis follows the CRISP-DM process and answers business-related questions on pricing, neighborhoods, amenities, and host behavior

## 📋 Table of Contents
- [Introduction](#introduction)
- [CRISP-DM Framework](#crisp-dm-framework)
- [Technologies Used](#Technologies-Used)
- [Business Questions](#business-questions)
  - Q1: What is the average Airbnb price by neighborhood?
  - Q2: How do bedrooms and bathrooms affect price?
  - Q3: Does host response time influence pricing?
  - Q4: What are the most common amenities?
  - Q5: Do more amenities mean higher price?
- [Conclusion](#conclusion)
- [Key Learnings](#Key-Learnings)
- [License](#License)
- [Acknowledgements](#Acknowledgements)
  
### introduction
Airbnb has revolutionized short-term rentals around the world, and Seattle is no exception. With thousands of listings to choose from, travelers and hosts alike are curious about what drives Airbnb prices. In this project, I used real Seattle Airbnb data to uncover key patterns that influence listing prices.
This analysis was completed as part of my Udacity Data Science Nanodegree using the CRISP-DM methodology. Let’s explore what insights I discovered.

### crisp-dm-framework
**1. Business Understanding**
 - What makes an Airbnb listing expensive?
 - Are hosts with faster response times able to charge more?
 - Do more amenities mean higher prices?

**2. Data Understanding**
- I used the listings.csv dataset from the Seattle Airbnb Open Data. It includes rich details like pricing, host behavior, amenities, and location.

**3. Data Preparation** 
I cleaned the data by,
- Removing symbols like $ and, from the price column.
- Filling missing values in numerical and categorical columns.
- Parsing amenities into a countable format.
- Dropping unnecessary or redundant columns.

**4. Data Analysis & Visualization**
- I explored five key questions using pandas, matplotlib, and seaborn.

### Technologies-Used
- Python
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

### business-questions
- #### What is the average Airbnb price by neighborhood?
  Some Seattle neighborhoods like Queen Anne and Capitol Hill have significantly higher average prices, suggesting popularity and proximity to key attractions

  This chart shows the average price distribution by neighborhood, helping us identify the most expensive and most affordable areas for Airbnb rentals.
  ![The Average Price](Image/Question-1.png)
- #### How do bedrooms and bathrooms affect the price?
  As expected, listings with more bedrooms and bathrooms generally charge higher prices, showing a positive correlation between space and cost.

  This analysis explores how listing prices vary depending on the number of bedrooms and bathrooms, helping understand property size vs price.
  ![Affect Price](Image/Question-2.jfif)
- #### Does host response time influence pricing?
  Hosts who respond within an hour tend to charge more, indicating that prompt communication may reflect professionalism and higher listing value.

  This visualization investigates whether quicker response times by hosts correlate with higher Airbnb prices.
  ![Time influence pricing](Image/Question-4.jfif)
- #### What are the most common amenities?
  The most common amenities include WiFi, kitchen access, heating, and essentials. These are expected features in most listings.
  
  This chart identifies the most frequently available amenities in Seattle Airbnb listings, such as WiFi, kitchen, heating, etc.
  ![common amenities](Image/Question-3.jfif)
- #### Do more amenities mean higher price?
  Yes. Listings offering more amenities generally charge more, though there's a saturation point beyond which the price increase is minimal.
  
  This analysis shows how the number of amenities in a listing affects its price, helping understand if "more features = more cost".
 ![more amenities mean higher prices](Image/Question-5.jfif)

### Conclusion
  This analysis revealed how price varies across Seattle neighborhoods and what factors—like space, amenities, and host behavior—contribute to higher Airbnb pricing.

### Key-Learnings
- Practiced data wrangling and cleaning with real-world data.
- Applied grouped visualizations to draw business insights.
- Improved understanding of feature-price relationships in a sharing economy.
  
### License
- This project is licensed under the MIT License – see the [License](License.txt) file for details.

### Acknowledgements
- Udacity for the project framework
- Airbnb for providing the open dataset
- OpenAI ChatGPT for project guidance and support




