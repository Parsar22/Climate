# Climate

The goal of this analysis is to understand the temporal patterns in sea surface temperature (SST) data from the North Pacific[https://raw.githubusercontent.com/Parsar22/Climate/main/Climate/north_pacific.csv] region. By applying various time series and spectral analysis techniques, we aim to identify dominant frequencies and trends, assess the spectral content, and explore relationships with other meteorological variables such as wind speed.
Data
This project utilizes two data sets EdGap_data.xlsx and ccd_sch_029_1617_w_1a_11212017.csv. The primary data set is the EdGap data set from EdGap.org. This data set from 2016 includes information about average ACT or SAT scores for schools and several socioeconomic characteristics of the school district. The secondary data set is basic information about each school from the National Center for Education Statistics.

Requirements
Software: Python 3+ pandas (for data manipulation) NumPy (for numerical computations) Seaborn or Matplotlib (for visualizations) scikit-learn (for machine learning models)

Analysis
Data Exploration:

Calculated summary statistics to understand data characteristics. Examined correlations between socioeconomic factors and ACT scores to identify key relationships. Visualized the relationship between free lunch percentage and ACT scores using a scatterplot. Created a bar chart to compare ACT scores across different income levels within states. Predictive Modeling:

Built a linear regression model and Random Forest Model to predict ACT scores based on socioeconomic factors. Developed a Random Forest model for potentially improved accuracy. Evaluated both models using metrics like Mean Squared Error (MSE) and R-squared.

Author
Parsa Rahimiderimi

License
This project is open source and can be used with references
