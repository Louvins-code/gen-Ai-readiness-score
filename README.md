# Generative AI Readiness Score – Indian SME Companies

## Business problem
Which small and mid-sized Indian companies, and which industries, are best placed to adopt generative AI? This project builds a simple score to measure that, so training and support can go where it is needed most.

## Data
- 100 company records across 10 industries (10 per industry), in `GenAI_Readiness_Score_SME.xlsx`
- **All data is synthetic.** I generated it for this project. Industry averages were set to reflect typical adoption patterns, so the results show how the model works. They are not real survey findings.

## Method
Each company is scored 0-100 on four parameters, then combined with weights (editable in the `Assumptions` sheet):

| Parameter | Weight | Meaning |
|---|---|---|
| Data Maturity | 30% | How well the company collects and uses its data |
| Digital Infrastructure | 25% | Cloud, software tools, system readiness |
| Skills and Talent | 25% | Digital and AI skills of staff |
| Leadership and Budget | 20% | Management support and AI budget |

Readiness levels: Beginner (below 40), Developing (40-59), Ready (60-74), Advanced (75 and above).

Sheets: `Industry Summary` (averages, rank, chart), `Data` (100 records with formulas), `Assumptions` (weights and levels).
Tools: Excel (AVERAGEIF, COUNTIFS, RANK, nested IF), Power BI for the dashboard.

## Key insights
1. **IT Services (77.9) and Fintech (75.0) score highest.** Agriculture (30.3) scores lowest, a gap of about 48 points.
2. **Only 33 of 100 companies are Ready or Advanced.** 50 are Developing and 17 are Beginner.
3. **Skills and Talent is the weakest parameter** (average 49.6, against 54-56 for the other three). Manufacturing is lowest on skills at 34.9.

## Recommendation
- Put training programmes first into Manufacturing, Textiles and Agriculture, where skills and data maturity are lowest.
- Start AI pilot projects in IT Services, Fintech and E-commerce, where every company is already Ready or Advanced.
- Since skills is the weakest area overall, a low-cost upskilling programme will lift readiness more than extra tools.

## Dashboard
Screenshots: add images in the `dashboard` folder.
