# oil-cost-optimization
Cost optimization analysis of Alberta oil facilities using production data and Python
# Cost Optimization Analysis – Alberta Oil Facilities

# Overview
This project analyzes Alberta oil production data to identify key operating cost drivers and recommend cost optimization strategies.

# Data
- Alberta Petrinex production data (January 2025)
- Synthetic operating cost assumptions aligned with industry patterns

# Methods
- Data cleaning and aggregation
- Cost per bbl normalization
- Correlation analysis
- Production volume segmentation

# Tools
- Python
- pandas
- matplotlib
- 
# Key Insights from Analysis
* Strong economies of scale: Higher production volumes consistently show lower $/bbl.
* Cost drivers are not equal:

  * Power costs show mid–high correlation with $/bbl
  * Maintenance costs show mid–low correlation
  * Labour costs show low correlation (largely fixed)

# Optimization Priorities (Ranked)

# 1️⃣ Power / Energy Costs — *Primary Lever*

Why focus here

* Strongest controllable driver of $/bbl
* Scales with run-time and efficiency
* Optimization does not directly reduce production

**Actions**
* Energy efficiency initiatives
* Equipment upgrades & automation
* Runtime and load optimization

**Expected Impact**: High, immediate

# 2️⃣ Maintenance Optimization — *Targeted, Not Reduced*

Why focus here

* Moderate correlation with $/bbl
* Poor maintenance increases downtime and unit costs

**Actions**

* Shift from reactive to preventive maintenance
* Focus spend on high-failure assets
* Reduce unplanned downtime rather than total spend

**Expected Impact**: Medium, sustained

# 3️⃣ Labour Costs — *Monitor, Don’t Cut*

Why not a priority

* Low correlation with $/bbl
* Largely fixed and safety-critical
* Cost reduction risks outweigh benefits

**Strategy**

* Maintain stable staffing
* Improve productivity via process efficiency

**Expected Impact**: Low

# Strategic Recommendation

> **Optimize controllable variable costs first (power, maintenance), then selectively scale efficient assets to maximize economies of scale.**

## Key Takeaway

* Cost efficiency is driven more by **how assets are operated** than by labour cuts
* Energy efficiency provides the highest ROI
* Scale amplifies efficiency, but only for low marginal-cost facilities

*This analysis demonstrates a data-driven approach to operational cost optimization aligned with real-world oil & gas constraints.*
