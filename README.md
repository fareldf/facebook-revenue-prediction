# Facebook Content Monetization Revenue Prediction and Analysis
## Business Understanding
As competitors' Facebook monetization revenue is not publicly disclosed, machine learning models are developed to estimate revenue using available performance metrics. These estimates competitive analysis and help identify opportunities to improve Pikiran Rakyat's Facebook monetization strategy.

## Objectivs
- Predict competitors' Facebook monetization revenue using machine learning models based on publicly available performance metrics.
- Analyze revenue patterns across media profiles and over time to uncover monetization strategies.
- Identify the key performance metrics that drive Facebook monetization revenue.

## Dataset
The data were obtained from two sources. First, Pikiran Rakyat's data were collected from Meta Business Suite and are not presented due to confidentiality restrictions. The second data were Competitors and they were downloaded from [SocialInsider](https://app.socialinsider.io/) and were collected between 1 and 7 June 2026 in a CSV format.

## Key Findings
- Developed a machine learning model to estimate Facebook Content Monetization Revenue using content characteristics, posting information, and engagement metrics.
- XGBoost achieved the best performance (R² = 0.7018, RMSE = 0.2744, and MAE = 0.0728) and was selected to estimate missing revenue values.
- Reach, Impressions, and engagement-related metrics were identified as the primary drivers of monetization revenue, while content type, caption characteristics, and posting time provided additional, but smaller contributions.
