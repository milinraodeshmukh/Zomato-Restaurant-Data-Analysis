# 🍽️ Zomato Restaurant Expansion Analysis  
## Advanced Excel Data Driven Analytics Project  
**Prepared By: Milin Rao Deshmukh**

## 📌 Project Overview  
This project analyzes **global restaurant data** to identify the best **countries and cities** for new Zomato restaurant openings.  
Using **Excel-based data cleaning, lookup automation, pivot tables, conditional formatting, and dashboard creation**, the project provides:

- Country-wise restaurant distribution  
- Customer satisfaction insights  
- Cost and cuisine analysis  
- Competition-level evaluation  
- Data-driven recommendations for expansion  

The final dashboard helps management analyze **year-wise, country-wise, and cuisine-wise** trends to support strategic decisions.

---

## 📊 Dataset Summary  

### **Tables in the Dataset**
- **Raw Data**  
- **Country Description**  

**Total Attributes: 21**  
- 20 from Raw Data  
- 1 from Country Description  

### **Categorical Columns (14)**  
CountryCode, RestaurantName, City, Address, Locality, LocalityVerbose, Cuisines, Currency,  
Has_Table_booking, Has_Online_delivery, Is_delivering_now, Switch_to_order_menu,  
Price_range, Country Name  

---

## 🧹 Data Cleaning  
- Replaced missing **Cuisines** (US) with most common cuisine → **Mexican**  
- Applied **VLOOKUP** to fetch Country Names  
- Created derived columns using **string functions** and **array formulas**  
- Standardized inconsistent text formats  

---

## 🔍 Key Analysis & Insights  

### 1. **Number of Restaurants per Country**  
- India has the highest number of restaurants.  
- Countries like **Philippines, Indonesia, and Qatar** show low competition.

### 2. **Restaurants Opened Each Year**  
- Dashboard includes year-wise timeline to analyze growth trends.

### 3. **Restaurants in India with Price Range = 4**  
- Count calculated using COUNTIFS → **388 restaurants**

### 4. **Average Number of Voters per Country**  
- Helps understand engagement and popularity.

### 5. **Average Rating (Price Range < 4 & Online Delivery)**  
- Calculated using AVERAGEIFS  
- **Average Rating = 3.2738**

### 6. **High-Potential Countries for Expansion**  
Countries with **high ratings + low competition**:

- 🇵🇭 **Philippines** → Avg Rating: **4.47**  
- 🇮🇩 **Indonesia** → Avg Rating: **4.29**  
- 🇶🇦 **Qatar** → Avg Rating: **4.06**

### 7. **Recommended Cities for Expansion**  
- Quezon City (Philippines) → **4.8**  
- Jakarta (Indonesia) → **4.36**  
- Doha (Qatar) → **4.06**

### 8. **Quality of Restaurants in Suggested Countries**  
- Philippines: **4.47**  
- Indonesia: **4.29**  
- Qatar: **4.06**

### 9. **Food Cost / Investment Analysis**  
Average cost for two (USD):  
- Indonesia → **$18**  
- Qatar → **$61**  
- Philippines → **$117**

**Recommendation:**  
Start with **Indonesia & Qatar** due to lower cost.

### 10. **Competitors with Low Ratings**  
- **Qatar**: Indian Coffee House (3.4), Mumbai Spices (3.4), Ponderosa (3.6)  
- **Philippines**: Cafe Arabelle (3.6)  
- **Indonesia**: Onokabe (3.7)

### 11. **Cuisine Analysis**  
Top-rated cuisines (Rating **4.9**):

- Philippines: European, Asian, Indian, Japanese, Sushi  
- Indonesia: Sunda, Indonesian, Sushi, Japanese  
- Qatar: Sunda, Indonesian, Sushi, Japanese  

**Recommendation:**  
Focus on **Sushi, Japanese, Sunda, Indonesian, and European/Asian cuisines**.

### 12. **Online Delivery & Table Booking Impact**  
Restaurants offering these services consistently show **higher ratings**.

### 13. **Pricing Trend & Rating Correlation**  
- Correlation = **0.7939**  
- Higher-rated restaurants generally charge higher prices.

### 14. **Price Range Distribution Across Countries**  
- India leads in low-cost restaurants.  
- Mid-range opportunities: Indonesia, Philippines, Qatar, Canada.

### 15. **Array Formula for Multi-Condition Filtering**  
Used to filter:  
- No online delivery  
- Lowest price range  
- Avg cost ≤ 250 INR  

---

## ⚙️ Methodology  

### **Data Cleaning**
- Missing value handling  
- Country lookup mapping  
- Derived columns creation  
- Text and array functions  

### **Analysis Techniques**
- Pivot tables  
- Conditional formatting  
- Lookup functions  
- Aggregation formulas  
- Slicers (Year, Country)  

### **Dashboard Features**
- Dynamic year slicer  
- Country-wise views  
- Restaurant distribution insights  
- Rating vs price visual  
- Competitor comparisons  
- Country recommendation panel  

---

## 💡 Final Recommendations  

### **Best Countries**
- Philippines  
- Indonesia  
- Qatar  

### **Best Cities**
- Quezon City  
- Jakarta  
- Doha  

### **Best Cuisines**
- Sushi, Japanese  
- Sunda, Indonesian  
- European, Asian, Indian  

### **Business Actions**
- Enable **online delivery & table booking**  
- Offer **high-rated cuisines**  
- Prioritize **low-competition, high-rating** markets  
- Start with **Indonesia & Qatar** for cost-efficient expansion  

---

## 🛠️ Tools Used  
- **Excel**  
  - VLOOKUP  
  - COUNTIFS / AVERAGEIFS  
  - Array formulas  
  - Text functions  
  - Conditional Formatting  
  - Pivot Tables  
  - Slicers  
  - Data Cleaning  

---

## 🚀 Conclusion  
This analysis highlights strong, data-backed opportunities for Zomato’s expansion.  
Countries like **Philippines, Indonesia, and Qatar** offer:

- High customer satisfaction  
- High-rated cuisines  
- Manageable competition  
- Lower investment requirements  

With customer-focused services and optimized pricing strategies, Zomato can scale effectively and profitably in these regions.

