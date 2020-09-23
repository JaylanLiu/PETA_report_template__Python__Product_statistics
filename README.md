# PETA_report_template__Python__Product_statistics
PETA report template using Ipython kernel to basically describe selected BGI genetics test datasets

## Author
Jilong Liu
liujiong@genomics.cn

## Supported data set
BGI Tianhua series.

## Analysis
1. Sample size totally and of top 20 cancer types
2. Actionable mutation detection rate of top 20 cancer types
3. Variants detection rate of top 20 genes
4. TMB score distribution in top 20 cancer types
5. MSI status distribution in top 20 cancer types

## Usage
Supposed that you have access to BGI-PETA database and to the selected data set:
```
$jwr -i PETA_report_template__Python__Product_statistics.ipynb -o output.html --token xxx --json_str xxx
```
'xxx' should replace your information.:
