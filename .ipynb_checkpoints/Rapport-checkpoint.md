# HR Report
## Profil that are the most likely to leave

This report is intended for our HR department to indetify which employee profil is the most likely to leave the company.

## Dataset

### Dimensions

The dataset is made of 10,000 rows about the past and current employees each row has 11 attributes which are the following :

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
