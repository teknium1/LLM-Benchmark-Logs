GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5734|±  |0.0145|
|             |       |acc_norm|0.6067|±  |0.0143|
|arc_easy     |      0|acc     |0.8384|±  |0.0076|
|             |       |acc_norm|0.8131|±  |0.0080|
|boolq        |      1|acc     |0.8642|±  |0.0060|
|hellaswag    |      0|acc     |0.6379|±  |0.0048|
|             |       |acc_norm|0.8223|±  |0.0038|
|openbookqa   |      0|acc     |0.3400|±  |0.0212|
|             |       |acc_norm|0.4480|±  |0.0223|
|piqa         |      0|acc     |0.8161|±  |0.0090|
|             |       |acc_norm|0.8275|±  |0.0088|
|winogrande   |      0|acc     |0.7459|±  |0.0122|
```
Average: 73.25

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2244|±  |0.0262|
|                              |       |acc_norm|0.2283|±  |0.0264|
|agieval_logiqa_en             |      0|acc     |0.4071|±  |0.0193|
|                              |       |acc_norm|0.4132|±  |0.0193|
|agieval_lsat_ar               |      0|acc     |0.2478|±  |0.0285|
|                              |       |acc_norm|0.2391|±  |0.0282|
|agieval_lsat_lr               |      0|acc     |0.4922|±  |0.0222|
|                              |       |acc_norm|0.5000|±  |0.0222|
|agieval_lsat_rc               |      0|acc     |0.6022|±  |0.0299|
|                              |       |acc_norm|0.5911|±  |0.0300|
|agieval_sat_en                |      0|acc     |0.7427|±  |0.0305|
|                              |       |acc_norm|0.7379|±  |0.0307|
|agieval_sat_en_without_passage|      0|acc     |0.4563|±  |0.0348|
|                              |       |acc_norm|0.4466|±  |0.0347|
|agieval_sat_math              |      0|acc     |0.3500|±  |0.0322|
|                              |       |acc_norm|0.3455|±  |0.0321|
```
Average: 43.77

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5368|±  |0.0363|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6748|±  |0.0244|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3605|±  |0.0300|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2507|±  |0.0229|
|                                                |       |exact_str_match      |0.1727|±  |0.0200|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2880|±  |0.0203|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2000|±  |0.0151|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4667|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3680|±  |0.0216|
|bigbench_navigate                               |      0|multiple_choice_grade|0.4990|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6600|±  |0.0106|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4442|±  |0.0235|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2485|±  |0.0137|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7017|±  |0.0341|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6673|±  |0.0150|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.3030|±  |0.0145|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2112|±  |0.0115|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1703|±  |0.0090|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4667|±  |0.0289|
```
Average: 41.76

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3745|±  |0.0169|
|             |       |mc2   |0.5537|±  |0.0154|
```