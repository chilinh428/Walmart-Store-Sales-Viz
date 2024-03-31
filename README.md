# Walmart Store Sales

Explore, analyze, and visualize data with Tableau

Link to my dashboard: [Walmart Sales Analysis Dashboard](https://public.tableau.com/app/profile/chi.nguyen6580/viz/WalmartSalesAnalysis_17102578635860/Dashboard1)

![Walmart Sales Dashboard](https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/2ff4fea4-8d27-4c8f-8354-d22d497cc043)

## About Dataset

This dataset was obtained from [Walmart Dataset (Retail)](https://www.kaggle.com/datasets/rutuspatel/walmart-dataset-retail/data). Walmart has provided a data combining of 45 stores including store information and monthly sales 05-02-2010 to 01-11-2012. This dataset contains 8 columns:

| Column                  | Description                            |
| :---------------------- | :--------------------------------------|
| store                   | Store number                           |
| date                    | Week of sales                          |
| weekly_sales            | Weekly sales                           |
| holiday_flag            | 1 - Holiday week, 0 - Non-holiday week |               
| temperature             | Gender of the customer making purchase |
| fuel_price              | Product line of the product solf       |  
| cpi                     | Prevailing consumer price index        |
| unemployment            | Prevailing unemployment rate           |

## Cleaning Process

- No duplicate and missing values found

- Create group from field `date`:
<img width="461" alt="Screenshot 2024-03-31 at 21 50 40" src="https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/48f958bf-1e8b-47ac-be53-b9c0b65a5f09">

## Explorations and Findings

<img width="278" alt="Screenshot 2024-03-31 at 23 29 27" src="https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/61350acc-9f25-44b2-acfa-c7386df91169">

<img width="612" alt="image" src="https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/9dae59eb-a163-411b-9f81-30e49bfd736b">

- Year 2011 has higher sales than 2010 and 2012. But missing data for January 2010, November and December 2012 may make the results unreliable.

- Year 2010 has highest average sales per month.

- Top 5 stores over 3 years are the same (store number 2, 4, 13, 14, 20), just different in ranking.

<img width="1081" alt="Screenshot 2024-03-31 at 21 54 13" src="https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/3eda2807-d4d9-405d-b8cb-5073540a2ccb">

- There is no significant difference in average sales on `Labour Day` and `Super Bowl` compared to normal dates.

- Christmas holiday introduces as the last days of the year, but people generally shop in the 51th week. So when we look at the chart, average sales on `Christmas` are lower than those on normal days while `Thankgiving` has higher sales between them.

- January sales are significantly less than other months. This is the result of November and December high sales. After two high sales month, people prefer to pay less on January.

<img width="930" alt="Screenshot 2024-03-31 at 21 55 03" src="https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/e154a504-119c-47c7-8471-62d40582d71f">

<img width="889" alt="Screenshot 2024-03-31 at 21 57 17" src="https://github.com/chilinh428/Walmart-Store-Sales-Viz/assets/165115957/ed483f71-4318-4463-b44c-bbf60be4378f">

