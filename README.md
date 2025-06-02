# Predicting_District-wise_GDP_based_on_NTL_Data_using_ML_Models.
Satellite-based night-time light (NTL) imagery has emerged as a powerful proxy for economic activity, particularly in regions where official data is sparse or delayed. This study leverages high-resolution NTL data from the VIIRS sensor to estimate Gross District Domestic Product (GDDP) across one of India’s most populous states, Karnataka. Monthly NTL composites were retrieved using Google Earth Engine, while corresponding monthly GDP estimates were derived by decomposing annual data with EViews.

While most prior studies focus on national or state-level GDP estimation, this work advances the field by targeting district-level predictions. This granularity offers a sharper view of local economic disparities and dynamics, enabling more informed decision-making for policymakers, business leaders, and development stakeholders. A robust machine learning pipeline is implemented, employing state-of-the-art models including AdaBoost, Random Forest, XGBoost, Gradient Boosting, and Extra Trees.

To better understand the impact of population heterogeneity on model performance, districts within each state are categorised into three population-based clusters. This stratification allows for a nuanced analysis of predictive accuracy across different demographic segments, illustrating how population dispersion affects the economic signal captured by NTL data.

The project concludes with a comparative assessment for Karnataka, evaluating the aggregated predictive accuracy of each model. The findings underscore the potential of satellite-derived night-time luminosity as a scalable, timely, and cost-effective tool for real-time economic monitoring in data-scarce environments. This research affirms the value of remote sensing in bridging data gaps and supporting evidence-based policy at granular administrative levels.

![image](https://github.com/user-attachments/assets/ca12f0ff-70d9-4a43-9136-9f0a05bb4f21)

