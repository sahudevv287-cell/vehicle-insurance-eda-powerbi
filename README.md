# Vehicle Insurance EDA Dashboard (Power BI)

An interactive 4-page Power BI dashboard performing exploratory data
analysis (EDA) on vehicle insurance customer data. It covers customer
demographics, regional distribution, customer response behaviour and
sales channel performance.

## Business Problem
An insurance company wants to understand who its customers are, how they
respond to the insurance offer, and which regions and sales channels drive
premium sales, so it can target the right customers and improve conversion.

## Dataset
- ~381K customer records
- Columns include: id, gender, age, region_code, vehicle_age,
  vehicle_damage, annual_premium, policy_sales_channel, vintage, response
- Source: [https://drive.google.com/file/d/14B4j6YgYpoom06VqKTrCuepE-t5SMFpO/view?usp=sharing]

## Key Metrics
- Total customers: 381K
- Customer age range: 20 to 85
- Average annual premium: ~30.56K
- Average vintage: 154.35
- Average response rate: ~12% (47K of 381K customers responded positively)

## Dashboard Pages
1. **Overview** - KPIs, response split, customers by vehicle damage and
   response, region distribution by max and min annual premium
2. **Customers** - Region distribution, gender split, age distribution,
   vintage distribution, vehicle age by gender
3. **Response Analysis** - Response conversion funnel, average premium by
   age, vehicle damage vs response rate, region vs vehicle age breakdown
4. **Sales Insights** - Average premium vs customer count by channel,
   top 10 sales channels, sales channel ranking by vehicle age

## Key Insights
- Only about 12% of customers responded positively, so the data is
  heavily imbalanced towards non-responders.
- Most customers are in their 20s, and customer count drops steadily with age.
- Average annual premium generally rises as customers get older.
- Region 28 has the largest customer base by a wide margin.
- Male customers are slightly more numerous than female customers.
- A few sales channels (such as 152) bring in most of the customers,
  so sales depend heavily on a small number of channels.
- Most vehicles are under 2 years old; vehicles older than 2 years are a
  small share of customers.

## Interactivity
Slicers for Gender, Region Code and Vehicle Age let you filter every page,
and navigation buttons switch between pages.

## Tools Used
- Power BI Desktop
- DAX (measures and calculated columns)
- Data cleaning and modeling (Power Query)
- Data visualization: treemaps, donut, funnel, gauge, ribbon, scatter, combo charts

## Files
- `EDA_VEHICLE_INSURANCE.pbix` - Power BI project file (open with Power BI Desktop)
- `EDA_VEHICLE_INSURANCE.pdf` - PDF export of the report

## Author
[DEV SAHU ] | [https://www.linkedin.com/in/sahudev/]
