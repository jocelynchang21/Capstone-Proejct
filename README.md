## Data-Driven Logistics Strategy for High-Growth Customer Segmentation for Swire Coca-Cola
[View my segmentation + delivery cost notebook](./segmentation_delivery_cost.Rmd)

[View Business Problem Document (PDF)](https://github.com/jocelynchang21/Capstone-Proejct/blob/main/business%20problem.pdf)

### Project Summary & Business Objective

Swire Coca-Cola aimed to optimize its logistics operations by identifying high-growth potential customers currently using white truck (ARTM) delivery and transitioning them to red truck (direct delivery). This strategic initiative supports scalable business growth while enhancing delivery cost efficiency. Our objective was to leverage data science techniques to uncover patterns in delivery cost and customer behavior, guiding a targeted shift in delivery strategy.

## Group’s Solution to the Business Problem

### Our group applied a multi-phase analytical approach combining:

- Predictive Modeling to estimate delivery costs and assess which ARTM customers could transition to direct delivery without increasing costs.

- Customer Segmentation using XGBoost with Classification Trees to identify distinguishing features of high-growth customers and support cross-validation of our results.

- Cost vs. State Analysis to evaluate the impact of delivery geography on cost performance, surfacing key cost-driving regions.

- Interactive Dashboards & Visualizations to enable ZIP-level and state-level exploration of cost patterns, volumes, and customer types.

This integrated approach allowed us to predict high-growth customer potential with accuracy, generate region-specific recommendations, and develop a transition roadmap for ARTM customers.

## My Individual Contribution

### As part of this project, I focused on:
- **Data Cleaning & Feature Engineering:** Addressed missing values, standardized formats, and created derived variables, such as unit cost and customer tier.

- **Segmentation-Based EDA:** Analyzed data by delivery type, state, product, and volume to surface trends and segment customers.

- **Predictive Modeling (SVR & XGBoost):** Built models to forecast delivery cost and used classification trees within XGBoost to profile high-growth customers. Tuned models using GridSearchCV and evaluated results using cross-validation.

- **State-Level Cost Visualization:** Designed a bar chart comparing average delivery cost across states, identifying cost-intensive regions and correlating them with delivery methods and customer density.

- **Interactive ZIP Code Map:** Developed a user-friendly tool to explore delivery costs by ZIP code, volume, and product type.

- **Insight Communication:** Packaged technical findings into business-ready recommendations and presented them to stakeholders to support strategic delivery shifts.
  
## Business Value of the Solution

### Our analysis empowers Swire Coca-Cola stakeholders to:

- **Identify Cost Inefficiencies:** Pinpoint ZIP codes and segments with high delivery costs to target with optimization strategies.

- **Forecast Demand More Accurately:** ARIMA and SVR models improve planning by identifying seasonality and trends.

- **Enhance Operational Planning:** Refine inventory and logistics processes to reduce delivery delays and excess stock.

- **Drive Market Expansion:** Use regional insights from SVR and customer segmentation to identify high-potential markets for growth.

- **Increase Profitability:** Reduce costs through logistics optimization and improve service levels, ultimately enhancing customer satisfaction.

## Challenges Faced

- Inconsistent and incomplete data, especially in rural ZIP codes and volume classifications.

- Model sensitivity, particularly with SVR, which required careful tuning to ensure accurate generalization across different volume tiers.

- Sparse data regions, which limited prediction reliability in some states and required us to flag those for further review.

- Balancing analytical depth with usability, ensuring models and visual tools were both robust and easy for stakeholders to interpret.

## What I Learned

### This project enhanced my skills in:

- Building and validating predictive models in real-world logistics contexts.

- Understanding cost behavior across geography and customer types, and how these insights support logistics optimization.

- Effective communication of data insights, using visualizations and storytelling.

- Strategic data application, where models not only predict but guide impactful business decisions.

- Cross-functional teamwork, aligning analytics with business priorities and feedback.
