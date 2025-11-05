# Case Study: Customer Churn Prediction

## Project Overview
This project focuses on predicting customer churn using IBM SPSS Modeler. By leveraging various data preparation and modeling techniques, we aim to identify high-risk customers and provide insights into customer retention strategies. The dataset used for this analysis is sourced from Kaggle.

## Team Members
- **Rikesh Yadav**
- **Mugdha Singh**
- **Pushpendra Kumar**

## Tools and Technologies
- **IBM SPSS Modeler**: A powerful tool for data mining and predictive analytics.
- **Dataset**: Sourced from Kaggle (Customer Churn dataset).

## Nodes and Tools Used
We utilized various nodes in IBM SPSS Modeler to perform data analysis and modeling:
- **Type Node**: Used to specify the type of data for each field in the dataset.
- **Table Node**: Used to load and display data in tabular form.
- **Statistical Node**: Applied to generate statistical summaries and insights for the dataset.
- **CHAID Model**: A decision tree-based algorithm used to predict customer churn.
- **Filter Node**: Applied to filter and preprocess the data for further analysis.
- **Export Node**: Used to export the final results into a flat file.
- **Distribution Matrix**: Analyzed the distribution of variables to understand the patterns and behaviors.
- **Auto Data Prep Node**: Automated the data preparation process for further analysis.
- **Select Node**: Used to select specific variables for analysis.
  
## Project Description
Customer churn prediction is a critical task for businesses aiming to reduce customer attrition and improve retention. This case study investigates the process of building a predictive model to forecast the likelihood of customers leaving a service.

The analysis involves:
1. **Data Preprocessing**: Cleaning and transforming the data to make it suitable for analysis.
2. **Exploratory Data Analysis (EDA)**: Using statistical tools to uncover insights and patterns.
3. **Model Building**: Applying decision tree algorithms (CHAID) to predict churn.
4. **Evaluation**: Assessing the model's performance using appropriate metrics.

## Dataset Details
The dataset used in this project is sourced from Kaggle, containing customer information such as:
- **Demographic details**
- **Customer activity data**
- **Service usage metrics**

The dataset is used to predict whether a customer will churn (leave) based on historical patterns.

## Steps Taken
1. **Loading the Dataset**: The data was imported using the Table node.
2. **Data Transformation**: Various transformations and cleaning steps were applied using the Type, Select, and Auto Data Prep nodes.
3. **Exploratory Data Analysis (EDA)**: We used the Distribution Matrix and Statistical nodes to perform EDA and better understand the data.
4. **Modeling**: A CHAID model was built using the CHAID Model node to predict customer churn.
5. **Filtering**: The Filter node was used to refine and prepare data for the model.
6. **Exporting Results**: Final results were exported to a flat file using the Export node.

## Results and Insights
The final model provides insights into the key factors contributing to customer churn. By analyzing the output, businesses can identify customers at high risk of leaving and take proactive measures to retain them.

## How to Run This Project
To run this project, you must have IBM SPSS Modeler installed. After downloading the project files, follow these steps:

1. Open the project in IBM SPSS Modeler.
2. Review the data and nodes used in the flow.
3. Run the process by executing each node in sequence.
4. Review the output results to analyze churn predictions.

## Acknowledgments
- **Kaggle** for providing the dataset.
- **IBM** for the powerful SPSS Modeler tool.
- **Our Team Members**: Rikesh Yadav, Mugdha Singh, and Pushpendra Kumar for collaborating on this project.

