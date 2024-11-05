# A/B Testing for Facebook Ads with Bandit Algorithms

## Project Description:

This repository implements two bandit algorithms, Thompson Sampling and Upper Confidence Bound (UCB), to optimize Facebook ad selection.

## Features:

- Thompson Sampling: Selects ads based on their historical performance, balancing exploration and exploitation.
- Upper Confidence Bound (UCB): Balances exploration and exploitation by considering both the average reward and uncertainty of each ad.
- Visualization: Visualizes the distribution of ad selections using histograms.

## Requirements:

* Python 3.x
* Libraries: pandas, numpy, matplotlib

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/<your_username>/Facebook-Ads-Bandit-Algorithms.git
2. **Install Libraries:**
   ```bash
   pip install numpy pandas matplotlib
3. **Run the Notebooks:**
   Open the `TSA_Facebook_ads.ipynb` and `UCB_Facebook_ads.ipynb` files in your preferred Jupyter Notebook environment and execute the code cells.

## Dataset:

The script assumes a CSV file named `Facebook_ads.csv` exists in the same directory. This file should contain data for each ad, including a CTR value (1 for click, 0 for no click).

## Note:

This project provides a basic implementation of bandit algorithms for ad selection. You can explore more advanced techniques and optimization strategies to improve the performance of your ad campaigns.

Feel free to explore the code, modify it, and adapt it for your specific A/B testing needs!
