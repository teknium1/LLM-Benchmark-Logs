GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5776|±  |0.0144|
|             |       |acc_norm|0.6177|±  |0.0142|
|arc_easy     |      0|acc     |0.8396|±  |0.0075|
|             |       |acc_norm|0.8215|±  |0.0079|
|boolq        |      1|acc     |0.8709|±  |0.0059|
|hellaswag    |      0|acc     |0.6495|±  |0.0048|
|             |       |acc_norm|0.8297|±  |0.0038|
|openbookqa   |      0|acc     |0.3360|±  |0.0211|
|             |       |acc_norm|0.4540|±  |0.0223|
|piqa         |      0|acc     |0.8188|±  |0.0090|
|             |       |acc_norm|0.8270|±  |0.0088|
|winogrande   |      0|acc     |0.7403|±  |0.0123|
```
Average: 73.73

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.1929|±  |0.0248|
|                              |       |acc_norm|0.2047|±  |0.0254|
|agieval_logiqa_en             |      0|acc     |0.3763|±  |0.0190|
|                              |       |acc_norm|0.3717|±  |0.0190|
|agieval_lsat_ar               |      0|acc     |0.2826|±  |0.0298|
|                              |       |acc_norm|0.2652|±  |0.0292|
|agieval_lsat_lr               |      0|acc     |0.5314|±  |0.0221|
|                              |       |acc_norm|0.5353|±  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.6134|±  |0.0297|
|                              |       |acc_norm|0.5911|±  |0.0300|
|agieval_sat_en                |      0|acc     |0.7427|±  |0.0305|
|                              |       |acc_norm|0.7233|±  |0.0312|
|agieval_sat_en_without_passage|      0|acc     |0.4709|±  |0.0349|
|                              |       |acc_norm|0.4660|±  |0.0348|
|agieval_sat_math              |      0|acc     |0.4045|±  |0.0332|
|                              |       |acc_norm|0.3727|±  |0.0327|
```
Average: 44.13

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5579|±  |0.0361|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6558|±  |0.0248|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3411|±  |0.0296|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2145|±  |0.0217|
|                                                |       |exact_str_match      |0.0947|±  |0.0155|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2980|±  |0.0205|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2057|±  |0.0153|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4800|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3880|±  |0.0218|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6750|±  |0.0105|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4353|±  |0.0235|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.3387|±  |0.0150|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7017|±  |0.0341|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6826|±  |0.0148|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.3200|±  |0.0148|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2120|±  |0.0116|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1697|±  |0.0090|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4800|±  |0.0289|
```
Average: 42.53

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4137|±  |0.0172|
|             |       |mc2   |0.5869|±  |0.0154|
```