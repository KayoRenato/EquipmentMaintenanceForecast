# EquipmentMaintenanceForecast

## Description
The idea is to have a Machine Learning model capable of predicting when each machine will need maintenance and thus avoid unscheduled downtime.

But before using a predictive model, top management needs to understand how the model makes predictions and which metrics have the greatest impact on the model's prediction.

## Data Dictionary
- Productivity (predictor variable) 
  - This is a measure of productivity, which describes the amount of time a machine is working at peak performance. The metric is a product of machine availability, performance and quality.
- Performance (predictor variable) 
  - This is the portion of products that come off the production line without defects and meet specifications without the need for any grinding work.
- Cost (predictor variable)
  - This is the cost of electricity, steam, oil or gas needed to produce a given unit of product in the factory.
- Priority (predictor variable)
  - Equipment priority when entering the maintenance period (Low, Medium, High).
- Efficiency (predictor variable) 
  - The amount of product a machine produces during a specific period. This metric can also be applied to the entire production line to verify its efficiency.
- Maintenance (target variable):
  - 0 means the equipment does not require maintenance (No)
  - 1 means the equipment requires maintenance (Yes)
