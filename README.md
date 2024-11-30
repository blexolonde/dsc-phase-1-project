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
I’m working with a dataset containing detailed aviation accident data with 19 columns, including:
- **Aircraft_Make**, **Aircraft_Model**: Aircraft type identifiers.
- **Total_Uninjured**, **Total_Fatal_Injuries**, **Total_Serious_Injuries**: Severity of injuries.
- **Flight_Phase**: Accident phases like takeoff, cruise, or landing.
- **Event_Date**: Accident dates for trend analysis.

I’ve cleaned and preprocessed the data to ensure consistency and accuracy.

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
