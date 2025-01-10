# Analyzing the Relationship Between Audio Exposure and Physical Activity Dynamics

## Objective

Investigate the impact of headphone audio exposure (volume) on physical activity and walking dynamics. Explore whether specific exposure patterns correlate with changes in walking performance, energy expenditure, or step count.

---

## Key Questions

1. Does higher audio exposure correlate with changes in walking performance?
2. Are there optimal audio exposure patterns for maintaining steady physical activity and enhancing walking dynamics?

---

## Data Requirements

### Apple Health Data

The following data is used for this analysis

- Headphone Audio Exposure
- Walking speed
- Active and basal energy burned.
- Daily step totals.

---

## Methodology

### 1. Data Integration

- Combine headphone audio exposure data with walking metrics and energy burned data.
- Align timestamps to analyze exposure patterns during physical activity.

### 2. Exploratory Analysis

- **Visualize Trends**:
  - Analyze walking performance based on headphone usage.
  - Examine relationships between headphone exposure energy burned, and walking parameters.
- **Correlation Analysis**:
  - Investigate whether different exposure durations or volumes lead to noticeable changes in walking dynamics or energy metrics.

### 3. Model Development

- **Predictive Model**:
  - Build a model to predict exposure rate based on walking performance or energy burned.

### 4. Insights and Recommendations

- Provide comments on the resulting data, and see if there is correlation between exposure rate and physical activeness.

---

## Deliverables

1. Insights into the impact of audio exposure on walking dynamics and energy expenditure.
2. A predictive model for exposure rates.
3. Ways to improve the model and the analysis method.

---

## Tools & Technologies

- **Data Processing**: Python, Pandas, NumPy.
- **Visualization**: Matplotlib, Seaborn.
- **Modeling**: Scikit-learn.

---

## Challenges & Considerations

1. **Exposure Metrics**:
   - Ensure accurate interpretation of audio exposure data (e.g., thresholds for "high" exposure).
2. **Causation vs. Correlation**:
   - Acknowledge that correlations do not imply causation between headphone exposure and activity metrics.

## Report

Make sure to read the report in order to understand the implementation of the code and the process behind it.
