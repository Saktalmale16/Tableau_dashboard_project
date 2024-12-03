# Hospitality Analytical Dashboard - Tableau
Welcome to the AtliQ Grand Hospitality Dashboard project! This project was created to provide insightful data analysis for AtliQ Grand, a luxury hotel chain facing revenue challenges in India's competitive hospitality market. Using Tableau and a comprehensive dataset, the dashboard provides crucial insights for strategic decision-making.

Link To : [Interactive Dashboard](https://public.tableau.com/app/profile/sakshi.talmale/viz/TableauprojectHospitality/Dashboard1)

# Project Overview
This Tableau project analyzes the performance of AtliQ Grand, a renowned luxury hotel chain, addressing revenue challenges and market share declines caused by increasing competition and ineffective management decisions. By utilizing interactive dashboards, the project provides actionable insights to optimize operations and increase revenue in the luxury and business hotel segments.

Key Metrics Analyzed:

Revenue trends,Occupancy %,Average ratings,Utilized capacity,Cancellation rates

These metrics are visualized using calculated fields and custom measures. The analysis includes tracking weekly performance trends, examining room utilization, and evaluating customer satisfaction to enable data-driven decision-making.

This project demonstrates a comprehensive data analytics process—from importing and validating data to creating calculated fields for tailored insights—showcasing expertise in data modeling (including relationships, joins, unions, and data blending) and visualization within the hospitality industry.

# Project Screenshot
![image alt](https://github.com/Saktalmale16/Tableau_dashboard_project-2/blob/b5968758d5bd279dd4b3f9a46410f807901497dc/Tableau%20Dashboard.PNG)

# Calculated Field
 
 Total Revenue = SUM([Revenue Realized])
 
 Average Rating = AVG([Ratings Given])
 
 Occupancy % = [Total Successful Bookings]/[Total Capacity] ELSE 0 END
 
 Utilized Capacity = SUM([Capacity])
 
 Cancellation Rate = [Cancellation Amount]/SUM([Revenue Generated])


# KPI Insights
  Total Revenue: 1,709

  Insight : The revenue indicates the current earnings for a specific period. While this figure is a baseline, comparing it to historical data or industry benchmarks can identify growth trends or areas needing 
  improvement.

  Actionable Insight: Investigate which segments (room type, customer demographics) contribute most to this revenue and optimize strategies for underperforming segments.

  Average Rating: 3.62

  Insight: A 3.62 average rating suggests moderate customer satisfaction. It indicates areas of improvement in services, amenities, or customer experience.

  Actionable Insight: Focus on customer feedback themes to improve services and aim for a higher rating (above 4.0), as this directly impacts customer retention and bookings.

  Occupancy Rate: 57.87%

  Insight: Occupancy at 57.87% is below the optimal range (typically 70-80% for high-performing hotels). This shows an opportunity to increase room bookings and overall utilization.

  Actionable Insight: Enhance marketing during off-peak seasons, introduce discounts or packages, and improve online visibility to drive higher occupancy.

  Cancellation Rate: 14.88%

  Insight: A cancellation rate of 14.88% is concerning, as cancellations directly affect revenue and occupancy rates.

  Actionable Insight: Analyze booking policies, cancellation patterns (time of cancellation, source of booking), and consider stricter policies or incentives for non-refundable bookings.

  Utilized Capacity: 232

  Insight: Utilized capacity measures how many rooms or resources were actively used. If 232 represents room nights or similar capacity, it can be compared to total available capacity to identify efficiency.

  Actionable Insight: Optimize pricing strategies for unutilized capacity during low-demand periods and explore upselling opportunities to maximize utilization.

  
# Informative Charts Insights  
Total Revenue by City and Category

Insight:
Identify which cities contribute the most to total revenue and which categories (e.g., room types, customer segments) are most profitable within those cities.
For cities with lower revenue in specific categories, investigate causes (e.g., lack of demand, competitive pricing).

Actionable Insight:
Focus marketing efforts on top-performing city-category combinations and explore opportunities to grow revenue in underperforming areas.
![image alt](https://github.com/Saktalmale16/Tableau_dashboard_project-2/blob/0272eac0fca0afa2f2004b683b3f390a864b530a/Cluster%20Column%20Chart.PNG)

% Revenue by Category
Insight:
This breakdown shows the proportion of revenue each category contributes to the total. Categories with the smallest share might have growth potential or need reevaluation.

Actionable Insight:
Diversify offerings in low-performing categories and capitalize on high-performing ones with upselling or cross-selling strategies.

Average Rating by City and Property Name
Insight:
Identify cities and properties with the highest and lowest average ratings. Poorly rated properties might indicate service or facility issues.

Actionable Insight:
Implement targeted improvement plans for low-rated properties and replicate successful practices from high-rated ones across the portfolio.

Revenue and Booking by Daytype (e.g., Weekday vs. Weekend)
Insight:
If weekends outperform weekdays, this indicates demand driven by leisure travelers. A reverse trend suggests a business traveler-oriented market.

Actionable Insight:
Tailor promotions based on demand patterns (e.g., weekend deals for leisure travelers or weekday packages for corporate clients).

Revenue by Room Class
Insight:
High-revenue room classes may indicate demand for premium offerings, while low-revenue classes may need pricing or marketing adjustments.

Actionable Insight:
Reevaluate pricing and amenities for underperforming room classes and offer bundles or upgrades to increase their appeal.

Total Revenue by Week Number and Category
Insight:
Analyze weekly revenue trends to identify peak and off-peak periods for each category. Seasonal patterns might emerge.

Actionable Insight:
Optimize staffing and inventory for peak weeks and introduce discounts or campaigns to boost revenue during slower weeks.

# Key Trackway

Identification of revenue trends, occupancy patterns, and customer satisfaction levels enables targeted strategies for improvement.

Insights into weekly performance, room utilization, and cancellation rates help refine decision-making processes and address inefficiencies.

Custom measures and calculated fields ensure tailored analysis, supporting AtliQ Grand’s goal of reclaiming market share and boosting profitability.

# Conclusion
The Tableau dashboard developed for AtliQ Grand provides a comprehensive analysis of the hotel chain's performance, addressing critical challenges like declining revenue and market share. By leveraging advanced data modeling techniques, such as relationships, joins, unions, and data blending, coupled with interactive visualizations, the project delivers actionable insights to enhance operational efficiency and revenue generation.This project not only demonstrates the power of data-driven insights in addressing real-world business challenges but also highlights the effectiveness of Tableau as a tool for sophisticated data analytics and visualization within the hospitality industry.
