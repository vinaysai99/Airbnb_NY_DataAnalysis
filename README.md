# New York Airbnb Data Analysis

![](https://github.com/vinaysai99/Airbnb_NY_DataAnalysis/blob/main/airbnb_ny_bing.jpeg)

## Project Overview
This project conducts **Exploratory Data Analysis (EDA)** on New York Airbnb listings to uncover insights into rental patterns, pricing, and host behaviors. By leveraging Python libraries such as **Pandas, Numpy, Matplotlib, and Seaborn**, we analyze and visualize trends to assist both guests and hosts.

---

## Objective
The primary goals of this project are to:
1. Analyze **room types, prices, and availability** across New York’s neighborhoods.
2. Understand **host behaviors** and patterns in listing management.
3. Detect and address potential **outliers** in pricing.
4. Provide actionable recommendations for guests and hosts based on data insights.

---

## Dataset
The dataset includes **20,765 entries with 22 features**. Key features include:
- **id**: Unique identifier for each listing  
- **name**: Listing title  
- **host_name**: Host's name  
- **neighborhood_group**: Borough where the listing is located  
- **latitude/longitude**: Geolocation data  
- **price**: Nightly rental price  
- **room_type**: Accommodation type (e.g., entire home, private room)  
- **reviews_per_month**: Average monthly reviews  
- **availability_365**: Number of available days per year  

---

## Workflow and Steps

### 1. Data Cleaning
- **Handling missing values**: Addressed nulls in `price`, `neighborhood`, and `beds`.
- **Outlier treatment**: Capped prices above $1,000 to avoid skewed visualizations.

### 2. Exploratory Data Analysis (EDA)
1. **Room Type Distribution**:
   - Visualized counts of each room type using **bar plots**.
   - Determined **Entire home/apt** as the predominant room type.

2. **Neighborhood Insights**:
   - Analyzed **price variations** across boroughs.
   - Manhattan emerged with the **highest average prices**.

3. **Availability Trends**:
   - Displayed correlations among `price`, `availability_365`, `number_of_reviews`, and `beds` using **heatmaps**.

4. **Price Distribution**:
   - Used **histograms** to analyze price distributions.
   - Most listings were in the **$50 - $300** range.

### 3. Data Visualization
- **Pairplot**: Showed correlations among `price`, `availability`, and `number of reviews`.
- **Heatmap**: Illustrated correlations among numerical features.
- **Histograms and Boxplots**: Identified outliers in `price`.
- **Bar Charts**: Depicted distributions of room types and neighborhood groups.

---

## Key Findings and Insights
1. **Pricing Patterns**:  
   - **Manhattan** listings are the priciest, followed by Brooklyn.  
   - **Entire homes/apartments** generally have higher prices compared to private or shared rooms.  

2. **Room Type Distribution**:  
   - Entire homes/apartments are the most common, with **private rooms** as budget-friendly alternatives.

3. **Price Outliers**:  
   - Detected listings priced at **$10,000+**, indicating extreme values that require filtering.

4. **Availability Trends**:  
   - Listings with **high availability** tend to have lower prices and more reviews, potentially indicating positive guest experiences.

5. **Host Patterns**:  
   - Certain hosts manage **multiple listings**, reflecting a shift toward professional hosting.

---

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/vinaysai99/Airbnb_NY_DataAnalysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the **Jupyter notebook** or **Python script**:
   ```bash
   jupyter notebook airbnb data analysis.ipynb
   ```

---

## Recommendations
- **For Guests**: 
   - Look for listings with high availability and good reviews for a better experience.
   - **Private rooms** in Brooklyn offer affordable stays compared to Manhattan.

- **For Hosts**:  
   - Improve **availability** and **review response rates** to attract more bookings.
   - Manage pricing effectively to compete within the borough's market.

---

## Future Work
- Use **machine learning** to predict prices based on room type and location.
- Perform **sentiment analysis** on reviews to better understand guest experiences.
- Create an **interactive dashboard** using Plotly or Tableau for live monitoring.

---

## Conclusion
This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using **EDA techniques**, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.

---

## License
This project is open-source and licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code.

---

## Contact
For any queries, feel free to reach out at:
- **GitHub**: [Vinay Mandala](https://github.com/vinaysai99)  
- **LinkedIn**: [LinkedIn](www.linkedin.com/in/vinaymandala99)  

---
