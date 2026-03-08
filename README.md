# -Feature-Engineering
**Project Overview**

This repository contains the feature engineering work performed for the machine predictive maintenance dataset. The goal of this task is to create additional meaningful features from the raw sensor data to improve machine learning model performance.

Feature engineering techniques such as rolling statistics and lag features were applied to capture machine behavior trends and temporal dependencies in the data.

**Feature Engineering Techniques Used
Rolling Features**

Rolling statistics were created to capture short-term trends in machine sensor readings.

Torque_roll_mean – Rolling mean of torque over a window of 5 observations.

Speed_roll_mean – Rolling mean of rotational speed over a window of 5 observations.

Torque_roll_std – Rolling standard deviation of torque to capture variability.

**Lag Features**

Lag features were created to include previous machine states.

Torque_lag1 – Previous torque value

Speed_lag1 – Previous rotational speed value

Wear_lag1 – Previous tool wear value

These features help the model learn patterns from historical data and improve predictive performance.

**05_feature_strategy(1).html**

This file contains the exported notebook showing the implementation of feature engineering techniques including rolling mean, rolling standard deviation, and lag features.

**Feature selection decisions_01.pdf**

This document explains the reasoning behind selecting and engineering features used for the machine learning model.

**Final modeling features.pdf**

This file lists all the final features used in the model, including both original dataset features and engineered features.
