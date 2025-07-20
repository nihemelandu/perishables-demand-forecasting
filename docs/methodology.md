# Problem Definition & Scoping

## 1.1 Original Business Problem Statement

**Stakeholder:** Operations Manager  
**Date:** 05/15/2025  
**Urgency:** High - Critical operational and financial impact

**Original Problem Description:**
> "Significant inventory waste and stockouts observed across multiple store locations for perishable goods; current demand forecasts fail to account for local trends, promotions, and seasonal factors, leading to suboptimal replenishment decisions."

## 1.2 Problem Decomposition

The operations manager's complaint encompasses multiple interconnected issues that need to be separated and prioritized:

#### A. Inventory Waste Issues
- **Core Problem:** Perishable goods expiring before sale
- **Impact:** Direct financial losses from disposal costs and lost investment
- **Measurable Aspect:** Waste percentage by product category and store location

#### B. Stockout Occurrences
- **Core Problem:** Empty shelves for perishable items
- **Impact:** Lost sales, customer dissatisfaction, and potential customer defection
- **Measurable Aspect:** Stockout frequency, duration, and revenue impact

#### C. Demand Forecasting Inadequacy
- **Core Problem:** Current forecasts ignore local market dynamics
- **Impact:** Poor replenishment timing and quantities
- **Measurable Aspect:** Forecast accuracy vs. actual demand patterns

#### D. Replenishment Decision Quality
- **Core Problem:** Suboptimal ordering decisions
- **Impact:** Perpetuating waste and stockout cycles
- **Measurable Aspect:** Order accuracy and inventory turnover rates

## 1.3 Problem Prioritization

Based on business impact and data availability assessment:

**Priority 1: Demand Forecasting Inadequacy**
- **Why First:** Root cause of downstream inventory issues
- **Business Impact:** Drives both waste and stockout problems
- **Data Availability:** Historical sales, promotional, and seasonal data likely available
- **Stakeholder Alignment:** Clear pain point affecting all store operations

**Priority 2: Inventory Waste Reduction**
- **Why Second:** Most measurable and immediate financial impact
- **Business Impact:** Direct cost savings from reduced disposal
- **Data Availability:** Waste tracking systems should provide good data
- **Stakeholder Alignment:** Visible problem with clear ROI potential

**Priority 3: Stockout Prevention**
- **Why Third:** Revenue impact but more complex to measure
- **Business Impact:** Lost sales and customer satisfaction
- **Data Availability:** May require combining multiple data sources
- **Stakeholder Alignment:** Important but impact harder to quantify

**Priority 4: Replenishment Process Optimization**
- **Why Fourth:** Dependent on solving forecasting accuracy first
- **Business Impact:** Long-term operational efficiency
- **Data Availability:** Requires integration of multiple systems
- **Stakeholder Alignment:** Process improvement with delayed benefits

## 1.4 Focused Problem Statement

**Primary Focus:** Demand forecasting accuracy for perishable goods

**Specific Problem Definition:**
"Develop forecasting capabilities that incorporate local trends, promotional activities, and seasonal factors to predict demand for perishable goods at individual store locations, enabling more accurate replenishment decisions."

**Measurable Objectives:**
1. **Forecast Accuracy:** Achieve 80%+ accuracy for weekly demand predictions
2. **Local Factor Integration:** Successfully incorporate store-specific trends and demographics
3. **Promotional Impact:** Accurately predict demand spikes during promotional periods
4. **Seasonal Adjustments:** Handle seasonal variations with <20% accuracy degradation

## 1.5 Success Criteria

**Primary Success Metrics:**
- **Forecast Accuracy Improvement:** >15% improvement over current baseline
- **Waste Reduction:** 25-40% decrease in expired inventory costs
- **Stockout Reduction:** 30-50% fewer stockout incidents
- **Implementation Timeline:** Working solution within 26 weeks

**Secondary Success Metrics:**
- **Store Adoption:** >90% of stores using improved forecasting
- **Inventory Turnover:** Improved turnover rates for perishable categories
- **Customer Satisfaction:** Measurable improvement in product availability scores

## 1.6 Scope Definition

### ✅ In Scope

These areas will be addressed in the current project. They align with the root causes of the business problem and are feasible given data availability and timeline.

| Scope Item | Description | Clarifying Questions |
|------------|-------------|----------------------|
| **Inaccurate demand predictions** | Improve forecasting for perishable goods at the store-product level. | - What exactly are we forecasting (daily, weekly, promo windows)?<br>- What is the current forecast accuracy baseline?<br>- What level of granularity is needed (store-product)? |
| **Local market influences** | Incorporate demographic, competitive, and neighborhood-specific data into forecasts. | - What local data is available?<br>- At what frequency and level of resolution?<br>- How is local behavior known to impact demand? |
| **Promotional impact modeling** | Use past promotions and outcomes to adjust future forecasts. | - Is promotion data structured and linked to sales outcomes?<br>- Can we isolate promo effects from other trends? |
| **Seasonality and external patterns** | Account for seasonal trends, events, and external demand drivers. | - How many seasonal cycles are modeled?<br>- Have recent years deviated from historical patterns? |
| **Forecast-driven replenishment guidance** | Deliver improved demand forecasts to support replenishment teams. | - Who will consume these forecasts (store managers, planners)?<br>- How are forecasts currently integrated into decisions? |

---

### 🚫 Out of Scope

The following areas are not included in this project. They fall outside the root cause domain or require separate solutions.

| Not in Scope | Reason | Clarifying Questions |
|--------------|--------|----------------------|
| **Manual ordering behavior** | Decisions remain with store teams; this project provides better inputs only. | - Who owns ordering decisions?<br>- Will behavior change be needed for adoption? |
| **Supplier/vendor management** | This initiative does not address upstream supply chain constraints. | - Are suppliers part of this planning process?<br>- Will forecasts affect procurement timelines? |
| **Product lifecycle forecasting** | Focus is on existing SKUs with historical data. | - How are new products handled?<br>- Is lifecycle forecasting owned by another team? |
| **Pricing optimization** | Forecasts will use current pricing as-is. No pricing changes will be recommended. | - Are pricing changes documented?<br>- Could pricing shifts affect model outcomes? |
| **Store layout and merchandising** | Physical display decisions are excluded. | - Are merchandising effects modeled or documented?<br>- Does store layout vary significantly? |
| **Waste disposal processes** | This project aims to reduce waste, not manage disposal logistics. | - Is waste cost data available for measurement?<br>- Who manages disposal at store level? |
| **Emergency procurement actions** | The model does not account for ad hoc procurement. | - Are emergencies common?<br>- Will this project affect their frequency? |

<!--
## 1.6 Scope Definition

**In Scope (Root Causes the Project Will Address):**
- **Inaccurate demand predictions** - Enhanced forecasting models incorporating local market factors
- **Ignored promotional impacts** - Integration of promotional calendar and historical promotional performance
- **Seasonal variation blindness** - Incorporation of seasonal patterns and weather-related factors
- **Local trend ignorance** - Store-specific demographic and competitive factors

**Out of Scope (Symptoms the Project Will Not Directly Address):**
- **Manual replenishment decisions** – The project will provide better forecasts, but ordering decisions remain with store teams
- **Supplier relationship management** – While forecast accuracy may improve supplier planning, vendor negotiations are outside scope
- **Product lifecycle management** – Focus is on existing products, not new product introduction forecasting
- **Pricing optimization** – The project will use existing pricing data but won't recommend price changes
- **Store layout optimization** – Physical merchandising and space allocation are not addressed
- **Individual waste disposal processes** – Focus is on preventing waste, not managing disposal logistics
- **Emergency procurement actions** – The project will predict demand, but emergency sourcing remains with procurement teams
-->
## 1.7 Assumptions & Constraints

**Key Assumptions:**
- Historical sales data is available and reasonably accurate across all stores
- Promotional calendar data can be accessed and integrated
- Store-specific demographic and competitive data is available
- Current inventory management systems can accommodate forecast updates

**Known Constraints:**
- Data quality may vary across store locations
- Limited to internal data sources initially
- Must integrate with existing replenishment workflows
- 26-week timeline for full implementation

**Risk Factors:**
- Data availability may be limited for newer store locations
- Seasonal patterns may have shifted due to external factors
- Store manager adoption may vary across locations

## 1.8 Stakeholder Alignment

**Primary Stakeholders:**
- **Operations Manager:** Problem owner, success criteria validation
- **Store Managers:** End users, practical implementation requirements
- **Merchandising Team:** Promotional planning context and constraints
- **Supply Chain Team:** Replenishment process integration
- **IT Team:** Data access, system integration requirements

**Success Validation Process:**
1. **Week 4:** Stakeholder interviews and data availability assessment
2. **Week 8:** Initial data analysis findings review
3. **Week 16:** Pilot store prototype demonstration and feedback
4. **Week 22:** Full solution testing and refinement
5. **Week 26:** Final solution deployment and approval

**Communication Plan:**
- Weekly status updates to Operations Manager
- Bi-weekly stakeholder reviews with store managers
- Monthly steering committee updates
- Ad-hoc consultations with merchandising and supply chain teams

---

## 1.9 Problem Translation to Data Science Task

**Data Science Task:**  
**Localized Time Series Forecasting for Perishable Demand**

**Translation Summary:**  
The core issue of inaccurate perishable demand forecasts is reframed as a data science problem focused on **forecasting future sales volume of perishable items at the store-product level**, while accounting for **exogenous variables** that impact demand. This enables improved replenishment decisions, reducing both spoilage and stockouts.

### **Task Formulation:**
- **Type:** Supervised Time Series Forecasting  
- **Target Variable:** Weekly (or daily) sales quantity per SKU per store  
- **Features (Covariates):**
  - Historical sales data
  - Local demographic indicators
  - Promotional activity calendars
  - Seasonal and holiday events
  - Weather and regional patterns (if available)

### **Modeling Approach:**
- **Baseline Models:** ARIMA, Exponential Smoothing (ETS)
- **Enhanced Models:** Time Series with Exogenous Variables (SARIMAX), Holt-Winters with seasonality
- **Alternative Options:** Gradient boosting or RNNs if traditional models underperform due to nonlinearity


### **Performance Metrics:**
- Mean Absolute Percentage Error (MAPE)
- Root Mean Squared Error (RMSE)
- Forecast bias (over/under-prediction tendencies)
- Business KPIs: Waste %, stockout duration, inventory turnover

### **Outcome Goals:**
- Improve forecast accuracy by >15%
- Reduce spoilage by 25%
- Decrease average stockout duration by 5 days
- Provide actionable insights via store-level dashboards for replenishment planners
---

*This methodology document will be updated as the project progresses through data discovery, analysis, and solution development phases.*
