# data-analyst-vaibhav
# Portfolio Project: School Category Analysis in Metro Vancouver

## Project Description  
This project analyzes the distribution of schools in Metro Vancouver, focusing on calculating the **proportion** and **percentage** of schools in specific categories (e.g., independent) within various geographical areas. By leveraging **AWS Glue DataBrew**, **AWS Glue Pipelines**, and **AWS CloudWatch**, this analysis provides valuable insights into the educational landscape of neighborhoods like Kitsilano and Downtown Vancouver.

The workflow includes dataset cleaning and profiling, pipeline automation, and monitoring to ensure reliable and accurate results.

---

## Objective  
The primary objectives of this project are to:  
- Calculate the proportion and percentage of schools in specific categories across Metro Vancouver.  
- Identify patterns and trends in the distribution of school categories within various geographical areas.

- 

  ![image](https://github.com/user-attachments/assets/a30d357d-e8bf-4259-9f88-c17268dcc387)


---

## Dataset  
The dataset was sourced from the Vancouver government website and includes the following key attributes:  
- **School Name**: Name of the school.  
- **Category**: Type of school (e.g., public, independent).  
- **Location**: Geographical area where the school is located.

- 

  ![image](https://github.com/user-attachments/assets/662eb064-7428-4e22-be1f-fc920e669d7f)


---

## Methodology  


### **1. Data Collection and Preparation**  
- Downloaded the dataset from the Vancouver government website.  
- Uploaded the dataset to **AWS Console** for processing.  
- Used **AWS Glue DataBrew** to:  
  - Clean the dataset by handling missing or inconsistent values.  
  - Profile the data to assess its quality and structure.

### **2. Pipeline Design and Automation**  
- Designed an automated data pipeline using **AWS Glue** to process the cleaned dataset.  
- Configured the pipeline to calculate proportions and percentages of school categories in different geographical areas.

- 

  ![image](https://github.com/user-attachments/assets/e6a19bd0-5b78-4f23-95f1-5dba868a3dc7)


### **3. Analysis**  

#### **Descriptive Analysis**  
- **Question**: What percentage of schools in a specific area fall into a particular category?  
- **Formula Used**:  
{Percentage of School Category in Area} = {Count of Specific School Category in Area}}\{Total Schools in Area}times 100
  
- **Result**:  
  - In Kitsilano, **55.56% of schools** are independent, reflecting the area's educational landscape.
 
  - 
 
    ![image](https://github.com/user-attachments/assets/12b1433e-040c-4ec2-a698-5017dc8fa86d)


#### **Exploratory Analysis**  
- **Question**: What is the proportion of schools in a specific category in a given geographical area?  
- **Formula Used**:  
  {Proportion of School Category} = {Count of Schools in a Category}/{Total Schools in Geo Local Area}

  
- **Results**:  
  - Metro Vancouver has **36 independent schools**.  
  - Downtown Vancouver has **2 schools**, with **1 being independent**, resulting in a proportion of **18% independent schools**.
 
  - 
 
    ![image](https://github.com/user-attachments/assets/c6e6e103-8076-4af8-8992-f09440fab460)


### **4. Monitoring and Validation**  
- Used **AWS CloudWatch** to monitor the pipeline’s performance and validate the results.  
- Ensured the pipeline executed reliably with accurate outputs.

---

## Key Findings  
- **Metro Vancouver**: There are **36 independent schools**, highlighting their prevalence in the region.  
- **Kitsilano**: Over half of the schools (**55.56%**) are independent, indicating a preference for this category in the area.  
- **Downtown Vancouver**: 18% of schools are independent, showing a lower concentration compared to other neighborhoods.  

---

## Tools and Technologies  
- **AWS Glue DataBrew**: For cleaning and profiling the dataset.  
- **AWS Glue Pipelines**: For automating the data processing workflow.  
- **AWS CloudWatch**: For monitoring the pipeline and validating results.

- 

  ![image](https://github.com/user-attachments/assets/0a7e22b9-1ae5-46f3-ba5b-04161dc07537)


---

## Deliverables  
1. **AWS Glue DataBrew Cleaning and Profiling Report**: Contains the steps and transformations applied to the dataset.  
2. **AWS Glue Pipeline**: Automates the data processing workflow to calculate proportions and percentages.  
3. **AWS CloudWatch Logs**: Verifies pipeline execution and highlights any anomalies.  
4. **Key Findings Report**: Summarizes the analysis results and insights.  


