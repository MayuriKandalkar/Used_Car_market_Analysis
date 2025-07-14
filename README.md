# Used Car Market Analysis

This project is all about understanding the Indian used car market using a dataset of cars that were sold across different cities in India. I cleaned and analyzed the data to discover useful patterns and insights. One of the most interesting things I found was that used cars generally fall into two major categories — budget cars and luxury cars. These insights can help businesses make smarter decisions and grow more effectively in this space.

This dataset provides detailed information on used cars, encompassing their Location, Kilometers_Driven, Fuel_Type, Transmission, Owner_Type, Mileage, Engine, Power, Seats, Price, Brand, and Car Age.

### Data Cleaning:
- Filling in Missing Data:  Any missing values in the dataset were handled carefully to avoid incorrect analysis.
- Standardizing Units:  Mileage values were converted to a common format, so comparisons would be meaningful like kilometers per liter (km/L) to kilometers per kilogram (km/kg)
- Simplifying Brand Names:  Some car brands had long or inconsistent names, so I shortened and standardized them.
- Removing Outliers:  I removed extreme or incorrect values to make the data more accurate and reliable.

### Exploratory Data Analysis (EDA):
**Feature Analysis:** I performed an in-depth analysis of individual feature distributions and     explored the relationships between variables, particularly their impact on the car price.

**Segment Discovery:** I found two main groups in the market - budget cars and luxury cars and     studied how they behave differently.

**Visualizations:** Using different charts like histograms, scatter plots, and heatmaps to spot    trends, fix errors, and remove unnecessary details

<br>

| Feature | Budget Cars | Luxury Cars |
| --- | --- | --- |
| City-wise Distribution | Mumbai leads the largest market followed by Hyderabad and Pune; Ahmedabad has the smallest share in market. | Coimbatore leads the largest market followed by Mumbai and Kochi; Jaipur has the smallest share in market |
| Fuel Type | Petrol and diesel vehicles dominate, while CNG and LPG have smaller share. | Diesel cars dominate, while Petrol cars represent a small fraction of the market. |
| Transmission Type | Manual transmission vehicles are significantly more prevalent. | Automatic transmission vehicles are significantly more prevalent. |
| Ownership | Majority are first-owner vehicles. | Majority are first-owner cars. |
| Seating Capacity | Most cars are 5-seaters, with 7-seaters being the next most configuration. | Most cars are 5-seaters, with 7-seaters being the next most configuration. |
| Brands Popularity | Maruti leads market, followed by Hyundai and Honda. | Mercedes-Benz leads market, followed by BMW and Toyota. |

### Key Takeaways:

*   The used car market in India is clearly divided into two major segments - budget and luxury cars - and each serve different buyer preferences.
*   Cities show different buying trends, so businesses should plan differently depending on the location.
*   **Budget cars** are usually manual and multi-fuel. on the other hand, **Luxury cars** are mostly automatic and run on diesel — showing different customer priorities.

### Who Can Benefit from This Analysis?

*   **Used Car Dealers**: They can use these insights to manage their stock better, set the right prices, and run effective promotions based on what customers in their area want.
*   **Online Car Platforms**: They can recommend the right cars to the right users, run better ads, and help sellers with smarter pricing.
*   **Banks and Finance Companies**: These organizations can offer car loans that suit different customer needs — whether they’re buying a budget car or a luxury one — and better manage the risks involved.

### Next Step

Build machine learning model for accurate used car price prediction and demand forecasting across segments and cities.
