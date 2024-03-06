# BAIML
Repository for all my projects as a part of Berkeley's AIML (BAIML) program

**amazon-coupon-acceptance**

This is the first of the practical applications project. The prompt.ipynb describes the details of the use case, data dictionary etc. 
The expectation is to submit this project with the appropriate visualizations, analysis and to apply skills learnt thus far in Modules 1 through 4
and answer the prompt question.  

The approach on analysis has been to 
1. Clean the dataset and remove if there are any redundancies.
     Removed `car` column as most of it was nulls and also
     Removed a small portion of null records.

2. Focus on one Coupon type (Bar) and analyze the various combinations 
    Capture the various metrics for bar related. 

    example template for metrics:
    ```
    {
      'non_null_data_pct': 0.9523021128981394,
      'accepted_pct': 56.93352098683666,
      'bar_pct':15.8374
      'bar_accept_pct': 0.41191845269210664,
      'bar_lt_3_vs_gt_3': 4.360544217687075,
      'accp_rate_bar_gt_1_age_gt_25': 1.3042071197411003,
      'accp_rate_bar_gt_1_pgr_nt_kid_occ_nt_farm': 0.38322487346348516,
      'accp_rate_gt_1_no_kids_not_widowed': 0.38322487346348516,
      'accp_rate_gt_1_under_30': 0.20694006309148266
     }```
  
