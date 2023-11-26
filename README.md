# INSURANCE-POLICY---DASHBOARD

 #### 1. Retrieving and Transforming Data

1.1-Retrive Data into Power BI from the dataset’s sheet name “Data”.
1.2-Add a column with Power Query named “Month Name” and retrieve month names from the date column “Expiry”.
1.3-Add a column with Power Query named “Amount (In Lacs)”. Get value from column “InsuredValue” and convert it into Lacs.
1.4—Add a conditional column named “Cust Type” IF “Amount (In Lacs)” > 50 then “Platinum”,
IF “Amount (In Lacs)” > 25 then “Gold”, IF “Amount (In Lacs)” <= 25 then “Silver”
1.5—Close and Apply. 
### Tools used
--->microsoft excel
--->power-bi
### 2. Create KPIs (Cards) with Measures.

2.1–Total Number of Policies.
2.2--Total Insurance Amount (In Lacs).
2.3–Total Number of Policies (Covered Earthquake and Flood).
2.4--Total Insurance Amount (Covered Earthquake and Flood).
2.5-- Create three Slicers with columns “Construction”, “Location” and “Cust Type”, “Place them at the Top right of
the Dashboard.

### 3. Create a Pie Chart

3.1—Create a Pie Chart with Columns “Construction” and “Total Insurance Amount (In Lacs)” measure.
3.2—Add Legend at the Top Left.
3.3—Add Data Label with Percent of Total.
3.4—Add “Total Number of Policies” in Tooltips.
3.5—Put the Title name “Construction by Insurance Amount”.


### 4. Create a Clustered Column Chart

4.1—Create a Clustered Column Chart with “BusinessType”, Insurance Amount (In Lacs), and Total Insurance Amount (Covered Earthquake and Flood) in Lacs.
4.2—Add Legend at the Top Left.
4.3—Add Data Label.
4.4—Add “Total Number of Policies” in Tooltips.
4.5—Put Title name “Business Type wise Insurance Amount”.

The total insurance Amount (Covered Earthquake and Food) is equal to the Insurance Amount where the Earthquake and Flood value is “Y”. 
### 5. Create a Pivot Table or Matrix

5.1—Create a Pivot Table or Matrix taking the Region and State in Rows and the Total Number of Policies, Insurance Amount (In Lacs), and Total Insurance Amount (Covered Earthquake and Flood) in Lacs in values.
5.2—Use Condition formatting and add a Data Bar for the “Insurance Amount (In Lacs)” Column.
5.3—Sort the data by Insurance Amount (In Lacs).
5.4—Add Sparkline, keep the “Total Number of Policies” measure on Y-Axis and the “Expiry” column on X-Axis.
5.5—Keep “Stepped Layout” Off
5.6—Put Title name “Region and State wise Details.”

### 6. Create a Decomposition Tree

6.1-—Create a Decomposition Tree with the Total insurance amount in Analyze and Explain by Region and Business Type.
6.2-Add Basic Formatting.

### Dashboard Overview
![image](https://github.com/Suthish-A/INSURANCE-POLICY---DASHBOARD/assets/133667688/dae97a25-4e01-4bb9-9ef2-782d0262971d)

