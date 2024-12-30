## SkyScore: Machine Learning for Passenger Satisfaction Insight

## Project Overview

SkyScore leverages machine learning to tackle the complex challenges faced by airlines in maintaining consistent service quality and ensuring passenger satisfaction. By analyzing key indicators, SkyScore enables airlines to proactively enhance service, predict passenger dissatisfaction, and optimize resource allocation.

### Problem Statement

Airlines operate extensive flight networks, which often lead to inconsistent passenger experiences due to varying service quality. Key challenges include:

- **Inconsistent Service Quality**: Struggles to deliver uniform experiences across flights.
- **Complex Satisfaction Management**: Travelers expect personalized and seamless service from booking to baggage claim.
- **Lack of Real-time Monitoring**: Satisfaction issues are often discovered post-incident through negative feedback.
- **Reactive Service Improvements**: Absence of predictive tools leads to a lag in addressing customer dissatisfaction.

SkyScore aims to address these issues by building a robust machine learning classifier to predict passenger satisfaction and enable airlines to act proactively.

## Objectives

- Develop a machine learning model to accurately predict passenger satisfaction.
- Utilize predictive insights to enable proactive service enhancements.
- Improve airline resource allocation to optimize passenger experience.

## Machine Learning Models and Results

We experimented with multiple machine learning algorithms to identify the best-performing model for predicting passenger satisfaction. The accuracy of each model is summarized below:

| Algorithm                | Accuracy |
| ------------------------ | -------- |
| XGBoost                  | 96.04%   |
| Random Forest            | 95.91%   |
| Long Short Term Memory   | 95.88%   |
| Decision Tree            | 94.96%   |
| Support Vector Machines  | 94.88%   |
| K Nearest Neighbor (K=9) | 92.48%   |
| AdaBoost                 | 88.47%   |
| Logistic Regression      | 83.51%   |

### Key Highlights

- **Best Performing Model**: XGBoost achieved the highest accuracy of 96.04%, making it the most reliable for predicting passenger satisfaction.
- **Model Variety**: Various algorithms were tested to ensure a comprehensive comparison and selection of the optimal model.

## Features Analyzed

The model analyzes a range of features including but not limited to:

- Customer demographics
- Flight details
- Service feedback
- On-time performance
- In-flight amenities

## Usage and Benefits

### For Airlines

1. **Proactive Issue Resolution**: Identify dissatisfaction trends before they escalate.
2. **Enhanced Passenger Experience**: Deliver personalized and superior service.
3. **Operational Efficiency**: Optimize resource allocation based on predictive insights.

### For Passengers

1. **Improved Satisfaction**: Experience consistent and tailored service.
2. **Seamless Journeys**: Benefit from enhanced operational efficiency and service quality.

## Future Work

- **Real-time Implementation**: Integrate real-time feedback and monitoring.
- **Scalability**: Expand features to cover additional aspects of the passenger journey.
- **User Interface**: Develop an intuitive dashboard for airlines to access insights and recommendations.

## Conclusion

SkyScore demonstrates the potential of machine learning to transform passenger satisfaction management in the airline industry. By predicting and addressing dissatisfaction proactively, airlines can elevate service quality and foster loyalty among travelers.

---


