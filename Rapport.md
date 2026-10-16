# HR Report
## Profile that are the most likely to leave

This report is intended for our HR department to indetify which employee profile is the most likely to leave the company.

## Dataset

### Dimensions

The dataset is made of 10,000 rows about the past and current employees, each row has 11 attributes which are the following :

### Variables

#### Description

| Variable | Description | Type | Why |
| :--- | :--- | :--- | :--- |
| `id` | Employee unique identifier | Quantitative | Tracks records |
| `satisfaction_level` | Employee satisfaction score | Quantitative | Measures morale |
| `last_evaluation` | Employee last evaluation score | Quantitative | Assesses performance |
| `number_project` | Employee number of project is involved in | Quantitative | Gauges workload |
| `average_monthly_hours` | Employee average monthly hours | Quantitative | Measures time input |
| `time_spend_company` | Employee time spent in the company | Quantitative | Tracks tenure |
| `work_accident` | Tells if the employee had a work accident | Qualitative | Records safety |
| `left` | Tells if the employee left the company | Qualitative | Target churn metric |
| `promotion_last_5years` | Tells if the employee was promoted in the past 5 years | Qualitative | Tracks advancement |
| `department` | Employee department | Qualitative | Groups organization |
| `salary` | Employee salary category | Qualitative | Categorizes pay |

#### Target

The target variable of the dataset is "left", it tells us if the employee has left the company. This variable is qualitative.
# TODO: Fournir une description de la variable cible et de sa distribution.

#### Not useful for the analysis

The id variable has no purpose in the analysis because it is just an identifier that has no meaning and is strictly technical.
The "satisfaction_level" variable also 





////// ma proposition pour les parties (vérifier la correctitude)
### Introduction
Since the director charged the department with the task of analysing the past and current employee database in order to figure out the raisons that would constitute the departure of a given employee. This report thus presents the results of that analysis.

### Preliminary Analysis
*Combien d'instances et combien de variables (attributs) y a-t-il ?*
There are 10'000 instances and 11 attributes/variables for each instance.

*Quelle est la variable cible et est-elle qualitative ou quantitative ?*
For this analysis the target attribute/variable that we are looking at is the #*left*# variable. This is a qualitative attribute, that can either take the values 0 or 1, with 0 indicating that the employee has not left the company, and 1 meaning that the employee did.

*Les autres attributs sont-ils quantitatifs ou qualitatifs ?*
CTRL C + CTRL V [tableau de Simon] 

*Certaines variables doivent-elles être supprimés de l'analyse ? Pourquoi ?* 
The variables to be eliminated should be:
ID - does not help to answer the question of whether or not an employee has left the company.
Satisfaction_level - does not help to answer the question either, even though it seems like it would, this variable is a quantitative one, not a qualitative one, meaning that this variable is not serving of any help.
Last_evaluation - does not help to answer the question, because it is a quantitative variable.
Number_project - does not help to answer the question, because it is a quantitative variable.
Average_monthly_hours - does not help to answer the question, because it is a quantitative variable.
Time_spent_company - does not help to answer the question, because it is a quantitative variable.

Work_accident - could help to answer the question, since it is also a qualitative answer, that has 2 values: 0 meaning that an employee did not have a work accident, and 1 meaning that an employee did.
Promoted_last_5years - could help to answer the question, since it is also a qualitative answer, that has 2 values: 0 meaning that an employee did not receive a promotion in the last 5 years, and 1 meaning that an employee did
Departement - could help answer the question, since it is also a qualitative answer, that gives out an extra information about where did an employee that has left the company had worked.
Qualitative - could help answer the question, since it is also a qualitative answer, that has 3 possible values: low, medium, high. It also represents an information that might have influenced the choice of an employee's departure.

*Y a-t-il des données manquantes ?*
No, there is not missing data.

*Fournir une description de la variable cible et de sa distribution.*
The target variable is the 

### Exploratory Analysis
#### Exploratory Analysis of qualitative variables (TP1-A)



