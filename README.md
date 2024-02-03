
# Certified Tableau Desktop Specialist

#### Technical Skills: Tibco Spotfire, Tableau, PowerBI, SQL, SQL Server Management Studio, PostgreSQL, Python, Excel with VBA, JMP Pro, LaTeX
#### Soft Skills: Project Management, Leadership, Effective Communication & Presentation

## Education & Relevant Certifications
- DeepLearning.AI: Natural Language Processing with Classification and Vector Spaces (_Jan 2024_) [Link](https://coursera.org/share/a2257e0e36e7f218e9fe5371852744d9)
- TDS-C01: Certified Tableau Desktop Specialist (_Jun 2023_) [Link](https://www.credly.com/badges/4830de97-b248-4c6d-9d03-922bc26f78bf/linked_in_profile)
- HackerRank SQL [Intermediate] (_Jun 2023_) [Link](https://www.hackerrank.com/certificates/ecf14b275651)
- B.S., Chemical Engineering: Technical University of Munich (_Sep 2020_)
- Dip., Chemical Engineering: Temasek Polytechnic (_Apr 2015_)

## Personal Projects

### Loan Defaulter Machine Learning Classification *<font size="3"> [Python, scikit-learn, Applied Machine Learning]  </font>*
[GitHub](https://yattavit.github.io/AI200_ML_Classification_Project_LendingClubLoanDefaultersPrediction/)

Business Case: Develop a Machine Learning model for the company to identify if the loan applicant is likely or unlikely to default on the loan, thereby assisting in the company's portfolio & risk assessment capabilities

Exploratory Data Analysis [EDA], feature-engineering & model testing was conducted using **Python** within the **JupyterNotebook** environment. Various feature engineering techniques & models were experimented & the best AUC scoring model was then selected & applied to form the final model.

The final model, along with the feature-engineered dataframe, acheived a **~90% predictive AUC score** after cross-validation via the Kaggle platform, thus demonstrating a strong ablity to discriminate between loan applicants whom are likely or unlikely to default on loans.

![Loan Defaulter Machine Learning Classification Project](/assets/img/Loan_Defaulter_Machine_Learning_Classification/ROC_Curves_for_CatBoostClassifier_Model_(Each_Fold).png)

### Shopee Code League: Logistics *<font size="3"> [Python]  </font>*
[GitHub](https://yattavit.github.io/Shopee_Code_League_Logistics/)

Background: Amidst the global COVID-19 pandemic, the surge in online orders on Shopee has heightened the importance of on-time delivery, a critical factor in e-commerce success. To meet this demand, Shopee has partnered with top-performing logistics providers across the region, enforcing SLAs and penalties to ensure timely deliveries. This rigorous monitoring and accountability process reinforces Shopee's commitment to delivering goods punctually, enhancing user confidence.

Task: Identify all the orders that are considered late depending on the Service Level Agreements (SLA) with Shopee's Logistics Provider.

![Shopee Code League: Logistics](/assets/img/Shopee_Code_League_Logistics/1.png)

### COVID-19_SQL_Tableau_Dashboard *<font size="3"> [T-SQL, SQL Server Management Studio, Tableau]  </font>*
[GitHub](https://yattavit.github.io/COVID-19_SQL_Tableau_Dashboard/)

Background: This project focuses on visualizing COVID-19 infection and deaths using data obtained from ['Our World in Data'](https://ourworldindata.org/covid-deaths) with Tableau. It aims to provide a visual representation of the detrimental impact of COVID-19 on a global scale & within the SEA region.

![COVID-19_SQL_Tableau_Dashboard_Global_Impact](/assets/img/COVID-19_SQL_Tableau_Dashboard/Global_Impact.png)

![COVID-19_SQL_Tableau_Dashboard_Global_Impact](/assets/img/COVID-19_SQL_Tableau_Dashboard/SEA_Impact.png)

### Hotel Revenue Analysis *<font size="3"> [PowerBI, PowerQuery M, T-SQL, SQL Server Management Studio, Excel, PowerPoint]    </font>*
[GitHub](https://yattavit.github.io/Hotel-Revenue-Analysis-Project/)

Business Case: A business manager of a chain of hotel would like to request help from the data analytics team to develop a dashboard to analyze & visualize hotel booking data

 - The business manager is interested if there’s any patterns/ seasonality with respect to:  
   1) Guests  
   2) Revenue  

Requirement: Build a Dashboard using **PowerBI** to provide at-a-glance information about features that are relevant to revenue

Data from raw .csv file was ingested into **SQL Server Management Studio [SSMS]**, from which SQL queries were iteratively built upon to obtain the final output which was then imported into SSMS for data analysis & visualization. Additional data processing was done in PowerBI with **PowerQuery M** for visualization purposes.

Guests, revenue seasonality, recommendation for staffing arrangement, and dataset limitations were explained with the help of additional visualizations done in PowerBI in the accompanying **Powerpoint slides**.

![Hotel Revenue Analysis](/assets/img/Hotel_Revenue_Analysis/Hotel_Revenue_Dashboard_Main.png)

### Analysis of Departmental Salary Disparities *<font size="3"> [Tableau, Python, T-SQL, SQL Server Management Studio, Excel, Powerpoint]      </font>*
[GitHub](https://yattavit.github.io/Analysis-of-Departmental-Salary-Disparities-Project/)

Business Case: The data analytics manager of a company would like to seek insights into salary disparities present within the company department

Objective:

 - Obtain relevant insights with Exploratory Data Analysis (EDA), and create a SQL query that identifies a high amount of variation within the department
 - Provide the top 5 department that should be selected for management to review, with regards to having the most variance & discrepancy in salary

Deliverables:
 - Provide a list from a SQL database with a way to score variation by Department
 - **JupyterNotebook** with accompanying **Python** code block for SQL calculation cross-validation & EDA

Data from raw .csv file was ingested into **SQL Server Management Studio [SSMS]**, from which SQL queries were iteratively built upon to obtain the final output which included the departmental:
1. Standard Deviation
2. Average Salary
3. Coefficient Of Variation
4. Outlier Count based off Z-Score values

The top 5 departments (along with reasons for selection) were flagged out for review, based on the calculated output. Further elaboration is done in the accompanying **JupyterNotebook** and **Powerpoint Slides**.

![Analysis of Departmental Salary Disparities](/assets/img/Analysis_Of_Departmental_Salary_Disparities/Top_5_Department_by_Salary_Disparities.png)

### Analysis of Credit Card Churning Customers *<font size="3"> [Tableau, Powerpoint]  </font>*  
[GitHub](https://yattavit.github.io/VI_Capstone_Credit-Card-Customers_Predict-Churning-Customers/)  

Analysis of attritted bank customers were performed based on various qualitative & quantitative measures using **Tableau** for data visualization.

Relevant recommendations that the bank can undertake to alleviate churning customers were proposed.
Limitations of the dataset which may lead to analytics bias was also discussed.
Further elaboration is done in the accompanying **Powerpoint Slides**.


![Analysis of Credit Card Churning Customers with Tableau](/assets/img/Analysis_Of_Credit_Card_Churning_Customers/viz_2.png)

### Numerical Investigation of Pressure Drop at Turbulent Flow Conditions in Single Pellet String Reactors *<font size="3"> [Computational Fluid Dynamics, LaTeX, OpenFOAM®, ParaView, Linux, C++] </font>*
[GitHub Repo](https://github.com/yattavit/TUM_Numerical_Investigation_SPSR)

**Achieved distinction for thesis.**

**Application:** **C++ Programming** was used in conjunction with **OpenFOAM®** in a Linux Distribution [Ubuntu] where modeling, mesh generation, and turbulent fluid simulations was conducted.

**ParaView** is used as both the GUI and post-processing tool to extract pressure drop, along with other parameters of interest. **LaTeX** was used for relevant graph plotting and the aggregation of all findings into a presentable format.

![Numerical Investigation of Pressure Drop at Turbulent Flow Conditions in Single Pellet String Reactors](/assets/img/TUM_Thesis/SPSR_FrontView_MeanderingFluidFlow.png)

## Work Experience

**Data Scientist @ NUHS (_Nov 2023 - Present_)**
- Application of NLP, free-text processing with Python for classification problems
- Development of **TIBCO Spotfire** dashboards for various departments within the healthcare cluster

**Process & Equipment Engineer II @ Micron Semiconductor Operations Asia (_Dec 2022 - Feb 2023_)**
- Continued to hold key appointment role as NPI Module Cycle Time Champion, delivered Module-wide presentation for proposed Diffusion Cycle-Time reduction initiative
- Achieved reduction in NPI Cycle Time from 112 day to 99day for NPI PWE and 97 to 90 days for NPI RAR line to speed up Yield Learning progress for tech node, thus contributing to Fab Yield Ramp as Module Cycle Time Champion
- Successfully achieved a challenging 5.5% Time-To-Mature Cumulative Yield (TTMCY) target by closely monitoring critical inline parameters via **macro creation for reporting purposes**
- Mentored new hires to improve their fundamental process understanding, problem-solving, and data analysis skills, resulting in their readiness to take up process ownership within 3 months

**Process & Equipment Engineer I @ Micron Semiconductor Operations Asia (_Dec 2021 - Dec 2022_)**
- Appointed as NPI Module Cycle Time Champion, which involved managing & communicating with various Process Owners to drive down 4 pillars of Cycle Time to acheive NPI manufacturing KPI target
  - Coordinated and enabled 2.5x capability on shared Workstation and achieved fab-target of 0 single-tool availability while serving as NPI Cycle Time Champion for Diffusion and Implant module
- Managed 5 NPI projects related to RTP, DPN & Poly processes relating to recipe improvement, FOAK tool qualification and photo scanner reject issue thus resulting in a cumulative 1.5% Yield Gain, 6% Manufacturing Availability improvement, 28% Recipe Processing Time Reduction and 50% improvement in photo scanner lot rejection per annum
- **Presented weekly analysis, plots, results, suggestions and directions to senior management and cross-faculty team members**

**Manufacturing Engineer @ Systems on Silicon Manufacturing Company Pte Ltd (SSMC) (_Jan 2021 – Jul 2021_)**
- Led root-cause investigation through data mining efforts for wafer scrap case and presented investigation findings to senior management. Implemented SOP to prevent future occurrences of wafer scrap resulting from identified root cause
- Collaborated with Automation Engineers in the development of **SQL/VBA Excel Sheet** for hourly Run, Queue, Hold WIP tracking system to identify and rectify production bottlenecks
- Coordinated production activities with manufacturing technicians, process, equipment, automation and industrial engineers to meet daily and monthly manufacturing goals through the efficient use of manpower, material, and machine

## Courses
- DeepLearning.AI: **Natural Language Processing** with Classification and Vector Spaces
- Heicoders Academy AI200: **Applied Machine Learning**
- Udemy, The Complete **SQL** Bootcamp: Go from Zero to Hero
- LinkedIn Learning **SQL** Essential Training
- Hackwagon IBF-DS101: **Data Science 101** Bootcamp
- Vertical Institute: IBF-**Data Analytics** Bootcamp
- DataCamp:  
  ▪ Data Visualization in **PowerBI**  
  ▪ Intermediate **Python**  
  ▪ Intermediate **SQL**  
- Google Data Analytics Professional Certificate: Data Analysis with **R Programming**
- University of California (Coursera): Project Management Principles and Practices
- University System of Georgia (Coursera): Six Sigma Yellow Belt
- Coursera Project Network: Creating an Interactive KPI Management Dashboard in **Tableau**
- University of Colorado (Coursera): **Excel/VBA** for Creative Problem Solving