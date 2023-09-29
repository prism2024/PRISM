# PRISM
This repository contains the source codes for PRISM and experimental data to support the claims in the paper "Accurate Detection of Overfitting Patches in Automated Program
  Repair through Semantic Anti-Patterns".

## Benchmarks
The directory [raw_data](./raw_data) contains all benchmarks used in our evaluation.
* [patches_tbar](./benchmark/patches_tbar) contains 329 patches generated by TBar.
* [patches](./benchmark/patches_tbar) contains 981 patches generated by 21 APR and developers.
  
## Data for figures and tables in the paper.
* [rq1.csv](./rq1.csv): (RQ1) Table 2. End-to-end repair performance of TBar with APCC
* [rq2.csv](./rq2.csv): (RQ2) Table 3. Performance of each APCC on large data set
* [rq2_threshold.csv](./rq2_threshold.csv): (RQ2) Figure 4. The change of CPR and IDR under the different threshold

## Source code
We currently provide only the source codes of our tool as a Anonymous GitHub repository: [link](https://anonymous.4open.science/r/Sprint-analyzer-6F4D/)
We will prepare the complete artifact including instructions for installition, scripts for reprocuding the results, etc., as soon as possible.
