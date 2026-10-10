# Logistics Delivery Reliability Analysis

## Project Overview
This project evaluates delivery appointment performance across customers and freight routes using logistics shipment and event data.

The analysis focuses on delivery reliability, out-of-window deliveries, pickup performance, detention, and data-quality limitations.

## Business Questions
- How does delivery appointment adherence vary over time?
- Which customers experience the highest number of out-of-window deliveries?
- How does pickup performance compare with delivery performance?
- How does the definition of on-time delivery affect reported performance?
- What data-quality limitations should decision-makers consider?

## Tools Used
- Microsoft Excel
- Microsoft Power BI
- DAX
- GitHub

## Dashboards
### 1. Service Performance
Provides an overview of delivery volume, delivery on-time rate, out-of-window deliveries, and detention.

### 2. Customer and Route Investigation
Examines delivery exceptions across customers and routes to identify areas requiring further investigation.

### 3. Definitions and Data Coverage
Documents KPI definitions, reporting scope, data-quality limitations, and interpretation guardrails.

## Key Findings
- 85,410 completed loads were represented in the dataset.
- The supplied delivery on-time rate was 44.61%.
- The strict-deadline delivery on-time rate was 33.28%.
- The difference between the two definitions was approximately 11.33 percentage points.
- On-time pickup did not consistently translate into on-time delivery.

## Data Quality and Limitations
- Facility-level geographic analysis was excluded because of inconsistencies in facility location data.
- Some trips contained contradictory timestamps.
- Missing fuel purchase records were not assumed to represent zero fuel consumption.
- The findings are descriptive and do not establish the causes of delivery delays.

## Conclusion
The analysis highlights the importance of consistent KPI definitions, customer-level performance monitoring, and data-quality validation when assessing logistics service reliability.
