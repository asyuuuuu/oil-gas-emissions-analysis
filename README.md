# oil-gas-emissions-analysis
To build a predictive model capable of forecasting carbon emissions for oil and gas companies, enabling stakeholders to make informed decisions for decarbonization.

Oil and Gas industry is one of major contributors for global economy, but it also contributes significantly to the greenhouse gas emissions. This project aims to analyze the challenges this industry faces in reducing its environmental impact and explore how data analysis can help pave the way towards a more sustainable future.

Problem Statement
* The oil and gas industry is under increasing pressure to reduce its carbon emissions.
* There is a need to analyze the relationship between carbon emissions and production levels to identify areas for improvement.
* The global goal is to achieve net-zero emissions by 2050.

* Main Goal: Quantify changes in carbon intensity over time and identify influencing factors.
* Main Objective: Calculate and compare carbon intensity across companies and commodities, and identify correlations with other variables.

Data Exploration & Insights
* The 'Production Value vs Total Emissions' scatter plot showcases a positive correlation, suggesting that increased production often leads to higher emissions, prompting a closer look at efficiency improvements.

* The 'Total Emissions Over Time' graph reveals a concerning trend: a significant surge in emissions, particularly between 1950 and 2020, underscoring the industry's   growing carbon footprint.


* The 'Emissions Over Time for Top 3 Commodities' line graph pinpoints the commodities with the highest emissions, guiding potential mitigation strategies.

* The 'Top 10 Entities by Total Emissions' chart highlights the major contributors to carbon emissions, emphasizing the need for targeted action.

Data Modeling- Features Selection
* * We employed various regression models to predict carbon emissions based on factors like production value, year, parent entity, and commodity.
* The 'r2 score' metric was used to evaluate model performance, indicating how well the model explains the variance in carbon emissions.
* The Multi Linear Regression model, incorporating all features, achieved the highest r2 score, suggesting its effectiveness in capturing the complex relationships in the data.

Data Modeling - Machine Learning Algorithm
* We further explored different machine learning algorithms, including Linear Regression, Random Forest Regressor, Ridge, and XG Boost Regressor.
* The 'Accuracy' and 'MSE' metrics were used to assess model performance, with higher accuracy and lower MSE indicating better predictions.
* The Random Forest Regressor and XG Boost Regressor models exhibited superior performance, showcasing their ability to handle non-linear relationships and complex interactions within the data.
* Cross-validation was employed to ensure model robustness and avoid overfitting

Model Deployment
* The final model was deployed using Gradio, creating an interactive interface for users to input data and receive carbon emission predictions.
* This deployment allows for practical application of the model, enabling stakeholders to assess the potential environmental impact of different production scenarios.

* Summary
* Our analysis successfully quantified the evolution of carbon intensity in the oil and gas industry, revealing a complex trend over time.
* Coal-related companies and commodities were identified as major contributors to carbon intensity.
* Correlations were uncovered, suggesting potential links between production volume, year, and carbon intensity, offering valuable insights for emission reduction strategies.
* * The trend of highest carbon intensity was observed between 1970 and 1985, likely due to factors such as high industrial activity, increased energy demands, and limited renewable energy adoption.
* The top 3 commodities contributing to emissions were identified as bituminous coal, oil and NGL, and anthracite coal.
* To achieve net-zero emissions by 2050, we recommend:
    * Government disincentives for fossil fuel consumption and incentives for renewable energy use.
    * Increased government investment in renewable energy infrastructure and research.
