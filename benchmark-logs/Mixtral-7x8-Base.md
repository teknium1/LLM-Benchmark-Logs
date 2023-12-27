GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5674|_  |0.0145|
|             |       |acc_norm|0.5964|_  |0.0143|
|arc_easy     |      0|acc     |0.8418|_  |0.0075|
|             |       |acc_norm|0.8346|_  |0.0076|
|boolq        |      1|acc     |0.8508|_  |0.0062|
|hellaswag    |      0|acc     |0.6489|_  |0.0048|
|             |       |acc_norm|0.8401|_  |0.0037|
|openbookqa   |      0|acc     |0.3520|_  |0.0214|
|             |       |acc_norm|0.4700|_  |0.0223|
|piqa         |      0|acc     |0.8232|_  |0.0089|
|             |       |acc_norm|0.8373|_  |0.0086|
|winogrande   |      0|acc     |0.7632|_  |0.0119|
```
Average: 74.18

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.1969|_  |0.0250|
|                              |       |acc_norm|0.1969|_  |0.0250|
|agieval_logiqa_en             |      0|acc     |0.3472|_  |0.0187|
|                              |       |acc_norm|0.3610|_  |0.0188|
|agieval_lsat_ar               |      0|acc     |0.2261|_  |0.0276|
|                              |       |acc_norm|0.1957|_  |0.0262|
|agieval_lsat_lr               |      0|acc     |0.3392|_  |0.0210|
|                              |       |acc_norm|0.3294|_  |0.0208|
|agieval_lsat_rc               |      0|acc     |0.4907|_  |0.0305|
|                              |       |acc_norm|0.4201|_  |0.0301|
|agieval_sat_en                |      0|acc     |0.7087|_  |0.0317|
|                              |       |acc_norm|0.6553|_  |0.0332|
|agieval_sat_en_without_passage|      0|acc     |0.4903|_  |0.0349|
|                              |       |acc_norm|0.4029|_  |0.0343|
|agieval_sat_math              |      0|acc     |0.4455|_  |0.0336|
|                              |       |acc_norm|0.3682|_  |0.0326|
```
Average: 41.85

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5895|_  |0.0358|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7344|_  |0.0230|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3411|_  |0.0296|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2061|_  |0.0214|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2740|_  |0.0200|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2029|_  |0.0152|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4167|_  |0.0285|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3840|_  |0.0218|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.5430|_  |0.0111|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.5536|_  |0.0235|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2495|_  |0.0137|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5414|_  |0.0371|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.4970|_  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2820|_  |0.0142|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2184|_  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1503|_  |0.0085|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4167|_  |0.0285|
```
Average: 39.45

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3403|_  |0.0166|
|             |       |mc2   |0.4851|_  |0.0145|
```