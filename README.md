# Supply Chain Analysis: Make vs Buy Decision  

## Project Overview  
This **Power BI** project aims to analyze the **Make vs Buy** decision for raw materials by evaluating **unit cost per volume**, **full cost**, and **capacity requirements**. 
The analysis helps manufacturers decide whether to produce materials in-house or purchase from suppliers.  

## Data Sources  
The dataset consists of four key tables:  

**`Quotes`** :Fact Table that involves Supplier, Quote ID, Part Number, Unit Cost, Volume, Non-Recurring Expenses. 

**`Product_Dimension`** Includes information about the product such as Part Number, Part Name, and Project  .

**`Internal_Mfg_Resource_Estimate`** : Contains information about the production capacity such as Unit Capacity ,
Machine Model, Machine Fixed Cost, Existing Capacity.

**`Supplier Yield`** : Includes supplier, and Yield Rate which is percentage of units that pass the quality test. 

## 📈 Dashboard Preview

![Cost_preview](https://github.com/user-attachments/assets/680f0770-cfaa-43e8-94c8-52441147db94)

### Cost Analysis Dashboard  
Provides insights into total cost, cost per unit, and supplier pricing trends  

### Volume Scenario Dashboard  
Analyzes volume-based cost fluctuations and investment needs  

## Key Metrics & Calculations  
**Extended Cost** – Unit cost multiplied by Volume  
**Full Cost Calculation** – Includes all recurring and non-recurring expenses  
**Volume Scenario Analysis** – Helps forecast demand impact on cost  
**Additional Capacity Required** – Determines if internal production can meet demand  
**Additional Investment Required** – Estimates capital needed for in-house production  
**Cost Avoidance** – Measures the difference between **Make vs Buy** scenarios  

## Business Insights & Strategic Recommendations  

 **Cost Efficiency through Volume Scaling**: As **purchase volume increases**, **unit cost decreases**, improving cost efficiency. 
 However, **non-recurring expenses (NRE) tend to rise**, requiring a balance between cost savings and upfront investment.  

 **Supplier Cost Variability**:  
- **Supplier Expellio** incurs the **highest non-recurring expense** for **Part Number P0380** at a volume of **$100K**, impacting total cost considerations.  
- **WidgetMakers, Inc.** offers the **lowest unit cost** for **Part Number P0604**, presenting a cost-saving opportunity.  

**Demand Forecasting & Volume Optimization**:  
- With a **forecasted demand of 48,000 units**, analysis suggests that ordering **50,000 units** optimizes cost efficiency, as the **full cost per unit decreases at higher volumes**.  
- At a **volume scenario of 75,000**, the **additional production capacity required** for **Part Number P1010** is **$35,727**, highlighting a need for resource planning.  

**Investment & Capital Planning**:  
- Expanding **in-house production** for **Part Number P1125** at **40,000 units** requires a **capital investment of $635,000**. 
- The estimated **full cost to manufacture 20,000 units** of **Part Number P0380** is **$16,300**, guiding pricing and profitability decisions.  

**Make vs. Buy Strategy**:  
- For **Part Number P1227** at a **volume scenario of 21,000**, purchasing externally is the recommended strategy, with **Expellio** identified as the most cost-effective supplier.  
- At a **volume of 99,000**, the total **expected purchase cost** for **Porlity (Part Name)** from **Ucell, We Make Supplier** is **$131,864.63**.  
