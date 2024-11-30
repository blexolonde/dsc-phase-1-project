# **Aviation Risk Analysis for Business Expansion**

## **Project Overview**
I aim to analyze aviation accident data to pinpoint the safest aircraft models for a company venturing into aviation. By examining historical safety data, I’ll recommend aircraft that are ideal for commercial and private operations, focusing on key safety metrics like injury severity, accident trends, and flight phase risks. This analysis is designed to provide actionable insights for business decision-making.

---

## **Business Question**
**"Which aircraft are the lowest risk for the company to start this new business endeavor?"**

To answer this, I evaluate:
- Survival rates and injury distributions by aircraft make and model.
- High-risk flight phases with significant injuries.
- Industry-wide safety trends over time.

---


## **Data Source**

The analysis is based on the **NTSB Aviation Accident Database**, a comprehensive dataset available on [Kaggle](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses). This dataset includes detailed records of aviation accidents, with essential fields such as aircraft make/model, accident dates, injury counts, and flight phases.

### **Datasets Used**

- **Raw Dataset (AviationData.csv)**  
  - Contains detailed aviation accident records with 31 columns and 88,889 rows.  
  - Includes fields such as aircraft make/model, accident dates, injury counts, and flight phases.  
  - Not cleaned; requires pre-processing for analysis.

- **Cleaned Dataset (aviation_data_clean.csv)**  
  - A streamlined version of the raw dataset with 18 essential columns and 48,090 rows.  
  - Contains cleaned and standardized fields for easier analysis.

### **Key Fields Used in Analysis**

| **Field Name**         | **Description**                                                                 |
|------------------------|---------------------------------------------------------------------------------|
| **Aircraft_Make**       | Manufacturer of the aircraft.                                                   |
| **Aircraft_Model**      | Specific model of the aircraft.                                                 |
| **Total_Uninjured**     | Total number of people uninjured in the accident.                               |
| **Total_Fatal_Injuries**| Total number of fatalities in the accident.                                     |
| **Total_Serious_Injuries**| Total number of serious injuries in the accident.                            |
| **Total_Minor_Injuries**| Total number of minor injuries in the accident.                                 |
| **Flight_Phase**        | Phase of flight during the accident (e.g., Takeoff, Cruise).                    |
| **Event_Date**          | Date when the event occurred.                                                   |
| **Purpose_of_Flight**   | Purpose of the flight (e.g., Business, Personal).                              |

---

## **Key Visualizations**
To tackle the business question and uncover insights, I’ve created these graphs:

### 1. **Box Plot: Total Uninjured by Aircraft Make and Model**
   - Visualizes survival rates by aircraft type.
   - **Insight**: Identifies aircraft with high survival rates for low-risk operations.

### 2. **Bar Plot: Fatal and Serious Injuries by Flight Phase**
   - Highlights the riskiest phases of flight.
   - **Insight**: Pinpoints critical phases needing enhanced safety measures.

### 3. **Line Plot: Number of People Involved in Accidents Per Year**
   - Displays injury and fatality trends over time.
   - **Insight**: Assesses safety improvements and highlights manufacturers with consistent safety records.

---

## **Methodology**
1. **Data Cleaning**:
   - Removed missing values from key columns.
   - Transformed dates and numerical fields for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Investigated injury severity, accident causes, and trends.
   - Grouped data by aircraft make/model and flight phase.

3. **Visualization**:
   - Used Python libraries like Matplotlib and Seaborn for compelling graphs.
   - Built Tableau dashboards for interactive exploration.

---

## **Insights and Recommendations**
### Key Findings:
1. **Low-Risk Aircraft**:
   - Aircraft with high survival rates and low injury counts are ideal choices for acquisition.

2. **High-Risk Flight Phases**:
   - Most fatal injuries occur during *Takeoff* and *Approach*. These phases require additional safety investments.

3. **Industry Safety Trends**:
   - Accidents and fatalities show a declining trend, reflecting improved safety technologies.

### Recommendations:
- Prioritize aircraft models with outstanding safety records (identified in the box plot).
- Invest in training and technology for takeoff and approach phases.
- Collaborate with manufacturers demonstrating consistent safety performance.

---

## **How to Run the Code**
1. **Prerequisites**:
   - Python 3.9 or higher.
   - Required libraries: `pandas`, `matplotlib`, `seaborn`.

2. **Steps**:
   - Clone this repository.
   - Place the aviation dataset (`AviationData.csv`) in the project folder.
   - Run the Jupyter Notebook to generate the analysis and visualizations.

3. **Interactive Dashboard**:
   - Open the Tableau dashboard file for deeper insights.

---

## **Project Structure**
```
.
├── AviationData.csv          # Dataset
├── README.md                 # Project documentation
├── aviation_analysis.ipynb   # Jupyter Notebook with analysis
├── tableau_dashboard.twbx    # Tableau workbook for interactive analysis
```

---

## **Future Work**
- Expand the analysis to include environmental and mechanical failure data.
- Develop predictive models for aviation risk evaluation.
- Integrate operational cost analysis to refine recommendations.

---

## **Contributors**
- **Blex Olonde**  
  Data Scientist | [LinkedIn](#) | [Email](mailto:blexolonde@gmail.com)

Feel free to contact me for questions or collaboration opportunities!

--- 
