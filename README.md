# Swire-Project
Predictive Maintenance for Swire Coca-Cola

Project Overview

Swire Coca-Cola faces significant annual losses due to unplanned machine downtimes across its production facilities. These downtimes impact the company’s ability to fulfill customer orders, currently meeting only 94.4% of demand. The goal of this project is to develop a Predictive Maintenance Pipeline that uses downtime and repair data to minimize these losses, improve machine reliability, and optimize production capacity.

Objectives

	•	Analyze Downtime Records: Identify patterns, severity, and root causes of machine downtimes using historical data from the Internal Warehouse Controller (IWC) system.
	•	Predict Downtime: Develop a machine learning model to forecast downtimes, allowing for preemptive maintenance.
	•	Optimize Inventory: Recommend stocking strategies for frequently required spare parts to reduce downtime durations.
	•	Provide Insights: Deliver actionable insights to improve production processes and extend machine lifespans.

Business Problem

Swire Coca-Cola operates six production plants and produces close to 192 million cases of beverages annually. The following challenges currently hinder production efficiency:
	•	Unplanned Downtimes: Machines unexpectedly break down, causing production lines to halt.
	•	Reactive Repairs: Spare parts are ordered post-failure, delaying repairs further.
	•	Opportunity Costs: These inefficiencies lead to substantial financial losses and reduced productivity.

Data Sources

Primary Dataset: IWC Work Orders

	•	Rows: 1.4M+
	•	Key Columns:
	•	ORDER_ID, PLANT_ID, FUNCTIONAL_LOC, ACTUAL_WORK_IN_MINUTES
	•	Machine attributes: EQUIPMENT_ID, EQUIPMENT_DESC, EQUIPMENT_CAT_DESC
	•	Maintenance types: MAINTENANCE_PLAN, MAINTENANCE_ACTIVITY_TYPE
	•	Insights:
	•	Severity of downtimes (planned vs. unplanned maintenance).
	•	Functional areas and machine-level details tied to breakdowns.

Supplemental Data

	•	Location Mapping: Links work orders to specific plants and production lines.
	•	Temporal Attributes: Execution start and end times for analyzing periodicity and trends.

Project Workflow

1. Data Exploration and Preprocessing

	•	Investigate downtime patterns across locations, machine types, and functional areas.
	•	Handle data quality issues like missing values or redundant entries.

2. Feature Engineering

	•	Develop features to answer what, when, why, where, how, and how much:
	•	What: Machine/component descriptions (frequent failure points).
	•	When: Downtime timestamps to identify patterns over time.
	•	Why: Breakdown conditions from IWC work order details.
	•	Where: Location-specific impacts on productivity.
	•	How Much: Opportunity costs measured in downtime minutes.

3. Predictive Modeling

	•	Train machine learning models to:
	•	Predict the likelihood of breakdowns based on operational data.
	•	Estimate remaining useful life (RUL) of critical components.
	•	Validation ensures accuracy and business applicability of predictions.

4. Prescriptive Analytics

	•	Recommend inventory levels for frequently replaced parts.
	•	Simulate production scenarios to test capacity optimization strategies.

5. Dashboard Development

	•	Key Deliverables:
	•	Interactive dashboards to communicate insights to stakeholders.
	•	Visualizations of predicted downtimes, financial impact, and recommendations.

Anticipated Outcomes

	•	Reduced machine downtime through early fault detection.
	•	Improved spare part inventory management.
	•	Enhanced production planning and capacity utilization.
	•	Estimated cost savings of $X million annually (to be validated via modeling).

Would you like me to further customize this or add additional sections (e.g., “Team Members,” “Tools Used”)? Let me know!
