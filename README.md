
# Google Ads Performance Analysis (90 Days)

For dashboard analysis please go through this link - https://public.tableau.com/app/profile/ayushi.mishra6535/viz/Book1_17704940057000/Dashboard1?publish=yes
Dashboard2 - https://public.tableau.com/app/profile/ayushi.mishra6535/viz/Book1_17704940057000/Dashboard2

##  Project Overview
This project analyzes 90 days of real Google Ads performance data to understand campaign behavior, user intent, cost efficiency, and optimization opportunities. The analysis combines multiple Google Ads data exports into a single analytical workflow to answer three key questions:

- What is happening in the account?
- Why is it happening?
- What actions can improve performance?

The focus of this project is not only visualization, but also **analytical reasoning, insight generation, and decision-making**, similar to how a real Google Ads or data analyst would work.

---

##  Dataset Description
The dataset consists of multiple Google Ads CSV exports combined into one analysis. Each file provides a different perspective on performance:

- **Campaigns** – Campaign-level performance metrics
- **Biggest Changes** – Comparison of campaign performance across two periods
- **Time Series** – Daily trends in clicks, impressions, CTR, and CPC
- **Search Terms** – Actual user search queries triggering ads
- **Devices** – Performance by mobile, desktop, and tablet
- **Networks** – Performance across Google Search and other networks
- **Day & Hour** – Performance by time of day and day of week
- **Optimization Score** – Google Ads recommendation-based score over time

---

##  Analysis Approach
The analysis follows a structured, professional workflow:

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Converting currency and percentage fields
   - Creating derived metrics such as CTR

2. **Exploratory Data Analysis**
   - Campaign-level comparisons
   - Trend analysis over time
   - Distribution and correlation analysis

3. **Behavioral & Intent Analysis**
   - Identifying high-intent vs low-intent search terms
   - Understanding user behavior across devices and networks
   - Linking CPC spikes to auction competition and search intent

4. **Cross-Dataset Insights**
   - Connecting campaign changes with time trends
   - Explaining cost inefficiencies using search term data
   - Validating optimization score impact against real performance

---

##  Key Insights
- Campaign performance is highly inconsistent due to uneven activation and budget pacing.
- When ads are active, CTR and engagement are healthy, indicating good ad relevance.
- A small number of campaigns and search terms drive most of the engagement.
- Many low-intent search queries generate impressions without clicks, leading to wasted spend.
- CPC spikes are driven by auction competition from irrelevant queries rather than increased demand.
- Mobile devices drive the majority of volume, while desktop traffic is more stable.
- Optimization Score is useful for account hygiene but does not directly guarantee better performance.

---

##  Recommendations
- Run campaigns more consistently to avoid long inactive periods.
- Focus budget on high-intent search terms and proven campaigns.
- Add low-performing, zero-click search terms as negative keywords.
- Optimize ad scheduling by concentrating spend during peak hours.
- Use Optimization Score selectively instead of blindly applying recommendations.

---

##  Tools & Technologies
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---


