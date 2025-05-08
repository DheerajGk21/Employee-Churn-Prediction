# IBM Employees Table Schema
 CREATE TABLE ibm_employees(
     EmployeeNumber INT,
     Age INT,
     Gender VARCHAR(10),
     Education VARCHAR(50),
     EducationField VARCHAR(50),
     MaritalStatus VARCHAR(10),
     JobRole VARCHAR(50),
     JobLevel INT,
     Department VARCHAR(50),
     MonthlyIncome INT,
     PercentSalaryHike INT,
     JobInvolvement INT,
     JobSatisfaction INT,
     EnvironmentSatisfaction INT,
     RelationshipSatisfaction INT,
     PerformanceRating INT,
     StandardHours INT,
     OverTime VARCHAR(10),
     NumCompaniesWorked INT,
     TotalWorkingYears INT,
     YearsAtCompany INT,
     YearsInCurrentRole INT,
     YearsWithCurrManager INT,
     TrainingTimesLastYear INT,
     YearsSinceLastPromotion INT,
     DistanceFromHome INT,
     WorkLifeBalance INT,
     BusinessTravel VARCHAR(20),
     Churn VARCHAR(10)
     );


# HR Employees Table Schema
CREATE TABLE hr_employees(
    satisfaction_level	INT,
    last_evaluation INT,
    number_project INT,
    average_montly_hours INT,
    time_spend_company INT,
    Work_accident INT,
    left_status INT,
    promotion_last_5years INT,
    Departments VARCHAR(20),
    salary VARCHAR(10)
 );
     
# MFG 10 Years Termination Schema
CREATE TABLE mfg_employees(
    EmployeeID INT,
    recorddate_key VARCHAR(20),
    birthdate_key VARCHAR(20),
    orighiredate_key VARCHAR(20),
    terminationdate_key VARCHAR(20),
    age INT,
    length_of_service INT,
    city_name VARCHAR(30),
    department_name VARCHAR(30),
    job_title VARCHAR(30),
    store_name VARCHAR(30),
    gender_short VARCHAR(10),
    gender_full VARCHAR(10),
    termreason_desc VARCHAR(20),
    termtype_desc VARCHAR(20),
    STATUS_YEAR INT,
    STATUS VARCHAR(20),
    BUSINESS_UNIT VARCHAR(30)
);

# Turnover Employees Schema
CREATE TABLE turnover_employees(
    stag FLOAT,
    event INT,
    gender VARCHAR(10),
    age INT,
    industry VARCHAR(30),
    profession VARCHAR(20),
    traffic VARCHAR(50),
    coach VARCHAR(30),
    head_gender VARCHAR(10),
    greywage VARCHAR(20),
    way VARCHAR(20),
    extraversion FLOAT,
    independ FLOAT,
    selfcontrol FLOAT,	
    anxiety FLOAT,	
    novator FLOAT
);

# Performance Metrics Schema
CREATE TABLE performance_metrics(
    dataset_name VARCHAR(50),
    model_name VARCHAR(50),
    accuracy FLOAT,
    precisions FLOAT,
    recall FLOAT,
    f1 FLOAT
);