## Delivery Cost Optimization – Case Competition Project
[View my segmentation + delivery cost notebook](./segmentation_delivery_cost.Rmd)

[View Business Problem Document (PDF)](https://github.com/jocelynchang21/Capstone-Proejct/blob/main/business%20problem.pdf)

### Project Summary & Business Objective

In this Project, our team's goal was to analyze delivery cost data and uncover actionable insights to support cost optimization and operational efficiency. The business challenge focused on the high variability in delivery expenses across product types, business segments, and volume ranges. The objective was to develop data-driven recommendations to reduce delivery costs while maintaining service levels and ensuring customer satisfaction.

## Group Solution

Our team cleaned and explored the dataset using exploratory data analysis to uncover key patterns, including cost discrepancies across ZIP codes and product categories. We applied ARIMA for time series forecasting and XGBoost for cost prediction. Results were visualized in an interactive ZIP code-level map to support targeted logistics and pricing strategies.

### Key Deliverables:
- Cleaned dataset 

- ARIMA forecasts of delivery trends

- XGBoost model for cost prediction

- Interactive sales map by ZIP code

- Business recommendations for reducing delivery expenses and enhancing operational efficiency

## My Individual Contribution

### As part of this project, I focused on:

- **Data Cleaning & Preprocessing:**  
I cleaned and standardized the dataset to prepare it for modeling. This involved addressing incomplete entries, correcting inconsistent formatting (ZIP code padding, string case normalization), and handling missing or negative values in cost-related columns. I also engineered relevant features such as cost per unit volume and flagged outliers for further analysis.

- **Exploratory Data Analysis & Segmentation:**  
I conducted a comprehensive EDA with a focus on identifying delivery cost drivers. To deepen insights, I applied segmentation techniques—grouping data by business segment, volume range, product type, and state. This allowed us to uncover cost patterns and outliers at both the ZIP code and state levels.  
Additionally, clustering techniques (e.g., K-means) were explored to identify latent segments of high and low-cost delivery areas based on geographic and volume-based characteristics.

- **Predictive Modeling (SVR & XGBoost):**  
I implemented both XGBoost and Support Vector Regression (SVR) models to predict delivery costs. While XGBoost captured complex feature interactions and non-linearities effectively, SVR offered strong performance in scenarios with fewer extreme outliers. I used GridSearchCV for hyperparameter tuning and cross-validation to assess model generalizability. The comparative performance of these models helped validate the robustness of our predictive framework.

- **Visualization: Delivery Cost vs. State (Bar Chart):**  
To enhance stakeholder understanding, I built a bar chart that visualized average delivery cost per state. This revealed that certain states consistently had higher costs, which were often tied to low delivery volume, long-haul shipping zones, or complex logistics needs.  
The visualization helped pinpoint high-priority regions for cost-reduction initiatives.

- **Insight: Relationship Between State and Delivery Cost:**  
Through segmentation and visualization, we uncovered a clear relationship between geography and delivery inefficiency. For instance, rural or low-density states like Wyoming and Montana exhibited disproportionately high costs per unit, driven by sparse delivery routes and smaller shipment volumes. This insight enabled the team to propose state-specific strategies, such as regional distribution hubs or delivery batching for cost reduction.

- **Interactive Visualization:**  
I created an interactive ZIP code-level sales and cost map using Python (Plotly & Folium), which enabled dynamic filtering by product type and volume range. This tool allowed stakeholders to explore patterns and potential savings opportunities at a granular level, supporting data-driven regional decisions.

- **Business Communication & Strategic Recommendations:**  
I synthesized analytical findings into strategic recommendations, highlighting key levers for reducing delivery costs and improving operational efficiency. These were presented in a concise, visual format tailored to both technical and non-technical stakeholders, sparking discussions on logistics partnerships and zone-based pricing optimizations.


- **Business Communication:** Synthesized findings into strategic recommendations and presented results to stakeholders in a clear and impactful format.

## Business Value of the Solution

### Our analysis empowers Swire Coca-Cola stakeholders to:

- **Identify Cost Inefficiencies:** Pinpoint ZIP codes and segments with high delivery costs to target with optimization strategies.

- **Forecast Demand More Accurately:** ARIMA and SVR models improve planning by identifying seasonality and trends.

- **Enhance Operational Planning:** Refine inventory and logistics processes to reduce delivery delays and excess stock.

- **Drive Market Expansion:** Use regional insights from SVR and customer segmentation to identify high-potential markets for growth.

- **Increase Profitability:** Reduce costs through logistics optimization and improve service levels, ultimately enhancing customer satisfaction.

## Challenges Faced

- **Data Quality:** Inconsistent or missing values, particularly in delivered_cases, required intensive preprocessing.

- **Data Sparsity:** Limited historical data for some products and regions reduced modeling confidence.

- **Business Alignment:** Translating technical findings into meaningful business recommendations required iterative refinement and collaboration.

## What I Learned

### This project enhanced my skills in:

- **Machine Learning & Forecasting:** Applied XGBoost and SVR in a real-world logistics setting.

- **Data Storytelling:** Communicated technical insights effectively through visuals and stakeholder presentations.

- **Team Collaboration:** Coordinated with peers across modeling, business, and visualization tasks to deliver a unified solution.

- **Strategic Thinking:** Learned how to align analytics with business objectives for maximum impact.
