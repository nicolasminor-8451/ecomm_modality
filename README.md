Ecommerce Modality Impact README

This project was created with the end goal to analyze the impact of ecommerce modalities on a households spend. To do so the code defined creates dataframes to be analyzed and repeated based on a different target period.
From the input of a target period, the project creates 5 dataframes:
The benchmark customer group
The target customer group
The ratio of post to pre period sales for the benchmark customer group
The ratio of post to pre period sales for the target customer group
The ratio of ratios of the target group per the benchmark group

The target period in question, the pre and post period are defined as 13 periods before and after the target period respectively

The benchmark customer group consists if households that used at least one ecommerce modality during the pre period but did not participate in an ecommerce modality during the target period and the post period
The target customer group consists if households that used at least one ecommerce modality during the pre period, target period and the post period
The ratio of ratio is defined as the ratio of the post to pre sales of the target group to the ratio of the post to pre sales of the benchmark group

The notebook can be manipulated for different target periods by changing the target period with the resulting dataframes being saved to the Azure Storage Space:
abfss://{sandbox}@{sa8451learningdev}.dfs.core.windows.net/users/n615602/ecomm_modality_impact

For this analysis 6 target periods were chosen from 2022P11-2023P3
