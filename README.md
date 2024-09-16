# Salifort Motors Employee Turnover
How can Salifort Motors imporve Employee Staisfaction and Minimize Turnover?

## Prepare

### Background
The human resources department at Salifort Motors has recently taken the initiative to collect data from their employees. The HR department is hoping this data can be leverage to instantiate some initiatives to improve employee satisfaction levels at the company.

### Stakeholders
* Salifort Motors Human Resources Department
* Salifort Motors Executive Leadership Team

### Business Task
Develop a machine learning model to predict whether an employee will leave the company. A successful model will allow the company to identify factors which contribute to an employee leaving the company, saving valuable time and money.

### Key Questions
1. Who are the employees most likely to leave?
2. Why do employees leave?
3. When do employees leave?

### Data Source
The data for this project was provided as part of the Google Advanced Data Analytics Certificate Program. The data set contained 14999 observations for each of the 10 columns present in the dataset. The data was synthetic and its only purpose was for use with this project.
#### Data Dictionary
![image](https://github.com/user-attachments/assets/20552b70-f616-44fd-a395-f8aef76ad85c)


### Initial Data Inspection (See `Initial_Exploratory_Data_Analysis.ipynb`)
To begin, it was necessary to get familair with the data. Necessary python packages were imported and the data was imported to a Jupyter Notebook. The data was inspected to see what data was present in the file as well as the format of the data in the different cokumns in the file. One main factor was then inspected at this point of the analysis, this was device type and whether that had a correlation on whether or not a user was more likely to churn. 

![image](https://github.com/user-attachments/assets/eb9fd339-dbe8-4efc-aa2f-82ba325d0d2c)

Ultimately, it was found that on average there are more iPhone users that were retained as well as more iPhone users that churned. This can likely be attributed to the fact that there were more iPhone users present in the dataset and thus they were more likely to both churn and be retained. Additionally, some more brief EDA showed that churned users tended to have less driving days, but also tended to have more drives and more distance traveled in these days. This provides some initial insight into what a churned users profile may be like. Churned users may be people who are only using the app on a road trip or vacation or a similar event while not needing the app for their everyday life.
## Analyze

## Construct

## Execute
