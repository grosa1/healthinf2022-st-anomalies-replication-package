## A robust approach for a real-time accurate screening of ST segment anomalies: Replication package

- `ml_algorithm_evaluation`: contains the jupyter notebooks used for the evaluation of the most fitting ML algorithm (Section 5.1)
    - `bin_result_img`: contains the evaluation results, saved as images, for RAST-BINARY
    - `ternary_result_img`: contains the evaluation results, saved as images, for RAST-TERNARY

- `validation`: contains the data related to the validation schemes for RAST
    - `rast_bin_random_forest`: experimental procedure for RAST-BINARY, using the Random Forest Classifier (Section 5.2)
        - `{4,6,8,10,16,32,64}beats`: contains the jupyter notebooks used for L1SO and 80-20 random-split validation schemes for each Temporal Window for the Heartbeat Observation
        - `result_analysis`: contains the jupyter notebooks used for the analysis of the results for RAST-BINARY
    - `rast_ternary_random_forest`: experimental procedure for RAST-TERNARY, using the Random Forest Classifier (Section 5.3)
        - `{4,6,8,10,16,32,64}beats`: contains the jupyter notebooks used for L1SO and 80-20 random-split validation schemes for each Temporal Window for the Heartbeat Observation
        - `result_analysis`: contains the jupyter notebooks used for the analysis of the results for RAST-TERNARY

The CSV files containing the data used for the experiment can be found [here](https://drive.google.com/file/d/13QZ_0jIxpSgn4dqSigpCwmD3rnbiGc-g/view?usp=sharing)



## How to cite
```
@inproceedings{rosa2022stanomalies,
  title={A robust approach for a real-time accurate screening of ST segment anomalies.},
  author={Rosa, Giovanni and Russodivito, Marco and Laudato, Gennaro and Colavita, Angela Rita and Scalabrino, Simone and Oliveto, Rocco},
  booktitle={HEALTHINF},
  pages={To appear},
  year={2022}
}
```
