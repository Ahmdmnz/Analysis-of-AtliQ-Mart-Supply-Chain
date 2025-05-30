# Project Background
Gujarat-based FMCG company AtliQ Mart lost key customers due to delivery problems and now needs to track three critical metrics daily: On-Time Delivery (OT%) measuring orders delivered on the promised date, In-Full Delivery (IF%) measuring orders with complete quantities, and On-Time In-Full (OTIF%) measuring orders that meet both criteria, all compared against customer-specific targets before expanding to new cities.

Insights & Recommendations

- **Service Level Performance Analysis**
  We focus on OTIF%, OnTime%, and InFull% to gauge overall delivery performance, track achievement against targets, and identify critical service gaps affecting customer satisfaction and retention.
  
- **City-wise Performance Comparison**
  Analyzing delivery metrics across Ahmedabad, Surat, and Vadodara helps identify location-specific challenges, optimize distribution networks, and establish regional benchmarks before expansion to new cities.
  
- **Customer Service Level Variations**
  Evaluating service metrics by customer highlights accounts at risk, reveals customer-specific patterns, and prioritizes improvement efforts for high-value or strategic relationships.
  
- **Product Performance Patterns**
  Tracking Line Fill Rate and Volume Fill Rate across product categories identifies specific inventory management challenges, informs procurement strategies, and ensures focus on high-impact product lines.

The power BI file [here](https://github.com/Ahmdmnz/Analysis-of-AtliQ-Mart-Supply-Chain/blob/main/SupplyChain.pbix)
# Data Structure & Initial Chcks
Spaero Technology's database structure as seen in the image consists of five main tables: Customers, Sales, Cash Flow, Target, and Dates, with a measurements table.
![image](https://github.com/Ahmdmnz/Analysis-of-AtliQ-Mart-Supply-Chain/blob/main/Screenshot%202025-05-21%20154532.png)

# Excutive Summary
## Overview of Findings
AtliQ Mart's delivery performance metrics show significant challenges across all service levels, with OTIF at only 29% against a 65% target. On-Time delivery (59%) and In-Full delivery (53%) are both substantially below their respective goals of 85% and 76%. While Volume Fill Rate remains strong at 97%, indicating product availability, the Line Fill Rate of 66% reveals critical issues in order fulfillment. These service gaps are consistent across all three operational cities and most pronounced with key customers like Acclaimed Stores and Coolblue, explaining the recent contract losses. Addressing these service level failures is essential before proceeding with planned expansion to additional metro markets.

Below is the overview page from the PowerBI dashboard and more examples are included throughout the report.

![image](https://github.com/Ahmdmnz/Analysis-of-AtliQ-Mart-Supply-Chain/blob/main/Screenshot%202025-05-21%20160557.png)

## Delivery Trends:
- OnTime performance at 59% is significantly below the target of 85%, with a critical -30.59% gap that indicates severe delivery timing challenges.
- InFull metrics at 53% versus a 76% goal show substantial product availability issues, with a -30.26% shortfall affecting customer order completion.
- The combined OnTime InFull (OTIF) rate of 29% is alarmingly low against the 65% target, with a -55.38% gap representing a major risk to customer satisfaction and 
  retention.
- Line Fill Rate at 66% suggests order lines are frequently incomplete, though Volume Fill Rate at 97% indicates that while order completeness is problematic, the  
  volume of products delivered is generally meeting expectations.
- This disconnect between Volume Fill Rate and other KPIs suggests the company is prioritizing high-volume items while smaller orders or specialty products face 
  fulfillment challenges.

  ![image](https://github.com/Ahmdmnz/Analysis-of-AtliQ-Mart-Supply-Chain/blob/main/Screenshot%202025-05-21%20161324.png)

## City Analysis:

- Surat leads with 30% OTIF (vs 66% target) and best OT rate (61%)
- All cities severely underperforming OTIF targets by ~36% gap
- Vadodara shows weakest performance at 28% OTIF (vs 64% target)
- OnTime metrics (58-61%) consistently outperform InFull metrics (52-54%)

## Customer Analysis:

- Top performers: Propel Mart/Viveks Stores (39% OTIF) vs worst: Acclaimed Stores (13%)
- 5 customers in green zone (37-39% OTIF), 7 in red zone (12-26% OTIF)
- OnTime execution varies dramatically (26-86%) while InFull more consistent (40-50%)
- Elite Mart shows unusual pattern: strong OnTime (85%) but poor InFull (29%)
- Atlas/Chiptec Stores lead OnTime (84%) while maintaining average InFull (~49%)

## Product Analysis:

- All products: high VFR (95-98%) vs modest LFR (64-68%)
- Best performers: AM Biscuits 750/AM Milk 500 (68% LFR)
- Weakest performers: AM Butter 250/500 (64-65% LFR)
- Minimal variation across product categories indicates systemic issues
- Consistent VFR excellence suggests volume prioritized over order completeness

  ![image](https://github.com/Ahmdmnz/Analysis-of-AtliQ-Mart-Supply-Chain/blob/main/Screenshot%202025-05-21%20161708.png)


## Recommendations:
## Supply Chain Optimization

- Address Critical OTIF Gap: Implement urgent action plan to close the 36% gap between current (29%) and target (65%) OTIF rates
- Improve Delivery Timing: Focus on logistics improvements to raise the OnTime performance from 59% toward 85% target
- Enhance Inventory Management: Align inventory with demand to elevate InFull rates from current 53% to target 76%

## Customer-Specific Strategies

- Implement Recovery Plans: Create dedicated improvement plans for lowest performers (Acclaimed Stores, Coolblue, Lotus Mart) with OTIF below 15%
- Leverage Success Models: Study best performers (Propel Mart, Viveks Stores) to identify replicable practices for 39% OTIF achievement
- Resolve Elite Mart Disconnect: Address root causes behind strong OnTime (85%) but poor InFull (29%) performance

## Geographic Performance

- Develop Surat Blueprint: Analyze and replicate factors behind Surat's marginally better OTIF performance (30%)
- Create City-Specific Interventions: Target unique challenges in Vadodara where OTIF performance is weakest (28%)
- Standardize Cross-City Operations: Implement best practices to reduce performance variance between cities

## Product Portfolio Management

- Strengthen Butter Category: Address specific challenges causing lowest LFR performance (64-65%) in AM Butter 250/500
- Replicate Success Drivers: Identify and scale factors behind stronger performance in AM Biscuits 750 and AM Milk 500 (68% LFR)
- Balance Volume vs. Completeness: Maintain strong VFR (97%) while improving LFR (currently 66%)

## Measurement & Analytics

- Implement Root Cause Analysis: Determine specific drivers behind the 55.38% OTIF gap to target
- Develop Leading Indicators: Create early warning metrics that predict delivery performance issues
- Establish Recovery Trajectory: Set milestone targets with clear timelines to achieve OTIF goals
