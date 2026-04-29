# Conversion-Funnel-ROI-Analysis

## Project Overview

This project analyzes candidate funnel performance and return on investment (ROI) across multiple recruiting sources to identify opportunities for improving conversion efficiency and optimizing spend. Using Python for data analysis and Power BI for visualization, the project provides insights into funnel drop-off, source effectiveness, and cost efficiency to support data driven decision making.

## Business Problem

Recruiting and marketing investments are significant, but it is unclear which sources and segments are driving the highest conversion outcomes and best return on investment. Leadership lacks visibility into:

- Where candidates drop off in the funnel
- Which sources produce the highest-quality candidates
- How much it costs to convert candidates by source
- Where to allocate budget for maximum efficiency

Without this insight, the organization risks inefficient spending and missed opportunities to improve conversion performance.

## Objectives
- Analyze candidate progression through the funnel stages
- Identify conversion rates across sources and segments
- Evaluate cost per conversion to measure ROI
- Detect high-performing and underperforming recruiting channels
- Provide actionable recommendations to optimize funnel performance and budget allocation

## Tools Used
- Python (Pandas, NumPy, Matplotlib)
- Power BI
- Excel / CSV

## Dataset
The dataset consists of 1,200 simulated candidate records representing recruiting funnel activity.

Key Fields:
- candidate_id – Unique identifier
- source – Recruiting source (Campus, LinkedIn, Referral, Job Board)
- school – Candidate school (for segmentation)
- stage – Funnel stage (Applied, Interviewed, Offered, Accepted)
- converted – Final conversion flag (1 = Accepted, 0 = Not converted)
- cost – Cost associated with acquiring the candidate

Data Characteristics:
- Funnel progression is simulated to reflect realistic drop-off patterns
- Sources have varying conversion probabilities and cost structures
- Dataset is designed to support meaningful ROI and performance analysis
  
## Methodology
1. Data Generation & Validation - Created a simulated dataset with controlled variation in conversion rates and costs across sources. Verified completeness and consistency.
2. Funnel Analysis - Calculated candidate counts at each stage to identify drop-off points in the funnel.
3. Conversion Rate Analysis - Measured conversion rates by source to determine which channels produce the highest success rates.
4. Cost & ROI Analysis - Calculated total cost and cost per conversion by source to evaluate efficiency.
5. Segmentation Analysis - Analyzed performance across schools and sources to identify high-performing segments.
6. Visualization - Built a Power BI dashboard to display funnel progression, conversion rates, and cost efficiency.

## Key Metrics
- Total Candidates: ~1,200
- Conversion Rate (Overall): ~8–12% (varies by simulation)
- Cost per Conversion: Varies significantly by source
- Funnel Drop-off: Progressive decrease from Applied → Accepted

## Results Summary
- Clear funnel drop-off identified: Candidate volume decreases significantly at each stage, with the largest drop typically occurring between early funnel stages (Applied → Interviewed).
- Source performance varies meaningfully:
Referral and Campus sources tend to have higher conversion rates, while LinkedIn and Job Boards show lower efficiency.
- Cost efficiency differs across sources:
Some sources generate conversions at a significantly lower cost, while others require higher investment per successful candidate.
- High-cost, low-conversion sources identified:
Certain channels contribute to higher spend without proportional conversion outcomes, indicating inefficiency.
- Segmentation opportunities exist:
Performance varies by school and source, suggesting targeted strategies could improve overall results.

## Business Recommendation

The analysis highlights clear opportunities to improve both conversion performance and cost efficiency:

- Reallocate budget toward high-performing sources such as Referral and Campus channels, which demonstrate higher conversion rates and lower cost per conversion
- Reduce or optimize spend on underperforming sources that show high cost and low conversion efficiency
- Focus on improving early-stage conversion rates, as small improvements at the top of the funnel can significantly increase overall conversions
- Implement ongoing KPI tracking through dashboards to monitor funnel performance and adjust strategy in real time

By optimizing both conversion rates and cost efficiency, the organization can improve ROI, reduce wasted spend, and make more strategic, data-driven recruiting decisions.

## [Dashboard](https://docs.google.com/presentation/d/12f5Gv2mVd9z9lYCP7LkJGZueJ-FacSupdMweQOQGP6M/edit?usp=sharing)

## Portfolio
View the full business case and dashboard summary in my [Notion portfolio](https://www.notion.so/Data-Science-Portfolio-6edb5c142bd5828688a901519a004abb?source=copy_link)
