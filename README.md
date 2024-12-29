# Car Evaluation Model Classification

This project performs classification on the **Car Evaluation dataset** to evaluate cars based on multiple features such as buying price, maintenance cost, number of doors, capacity, luggage boot size, and safety level. The model predicts the overall evaluation of the car as one of the four classes: **unacceptable (unacc)**, **acceptable (acc)**, **good (good)**, or **very good (vgood)**.

## Dataset

The dataset used in this project is the **Car Evaluation dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/19/car+evaluation). The dataset consists of 1728 instances and 6 categorical features.

### Features:
- **buying**: Buying price of the car (vhigh, high, med, low)
- **maint**: Maintenance cost (vhigh, high, med, low)
- **doors**: Number of doors (2, 3, 4, 5more)
- **persons**: Capacity in terms of persons to carry (2, 4, more)
- **lug_boot**: Size of the luggage boot (small, med, big)
- **safety**: Estimated safety of the car (low, med, high)

### Target:
- **class**: The overall evaluation of the car (unacc, acc, good, vgood)

## Installation

To run this project, make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

