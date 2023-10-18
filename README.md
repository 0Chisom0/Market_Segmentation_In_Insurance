# DEMO
![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/2e0deece-d0ab-439e-a325-767cb75fc9fd) ![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/4ea4ff6f-8e4b-4e76-a71d-b78d6cf686d3) 





# Market_Segmentation_In_Insurance
Market segmentation is a marketing strategy used in every field, that uses well-defined criteria to divide a brand's total addressable market share into smaller groups. Each group, or segment, shares common characteristics that enable the brand to create focused and targeted products, offers and experiences. In this case we are given an insurance customer dataset for customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.


# Data Description
The sample Dataset summarizes the usage behavior of thousands of active credit card holders during a 6 month span. The file is at a customer level with 18 behavioral variables.


# Dataset
Customer Data.csv

# Tools Used
#modules used 
Numpy
Matplotlib
Seaborn
Pandas
SKlearn
Pickle

# Deployment of Final Model
Creating a Streamlit Application based on our K-Means Clustering algorithm. By using customer details & identifying which cluster the customer belongs to. To deploy this project run in the command prompt of Visual Studio where all your files are.
![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/907d6949-92c1-4162-b0e2-38dcf8b81ade)


```bash
  pip install streamlit
```
```bash
  #Access the Streamlit folder for the app.py file by using command prompt instructions
  cd Streamlit
```

  ![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/5d685c68-21b3-4963-a031-d77ee0bd3fc9)
  
```bash
    #install virtual environment
    pip install pipenv
```

![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/ca355a45-3084-49bc-a9de-94394dd3551a)


```bash
    #create virutal environment to run streamlit application
    pipenv shell
```

![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/381c6e71-e044-4d4a-b460-59de8fba7a9b) 

```bash
    #Add modules that are being referenced in the app.py file
    pipenv install streamlit scikit-learn pandas plotly matplotlib seaborn pickle
```
![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/cfc5f1eb-100b-4c02-b76c-7c0e682e4b94)


```bash
    #Launch streamlit application on your local server
      pipenv run streamlit run app.py     
```
![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/1075debe-effa-4d01-a65a-3c107f38e7a8)

```bash
    #Final Product Below
```
![image](https://github.com/0Chisom0/Market_Segmentation_In_Insurance/assets/122185866/2e0deece-d0ab-439e-a325-767cb75fc9fd) 

# Test completed
K-Means Clustering
Decision Tree


