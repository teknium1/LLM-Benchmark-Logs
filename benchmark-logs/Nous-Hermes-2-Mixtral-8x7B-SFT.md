GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5904|±  |0.0144|
|             |       |acc_norm|0.6323|±  |0.0141|
|arc_easy     |      0|acc     |0.8594|±  |0.0071|
|             |       |acc_norm|0.8607|±  |0.0071|
|boolq        |      1|acc     |0.8783|±  |0.0057|
|hellaswag    |      0|acc     |0.6592|±  |0.0047|
|             |       |acc_norm|0.8434|±  |0.0036|
|openbookqa   |      0|acc     |0.3400|±  |0.0212|
|             |       |acc_norm|0.4660|±  |0.0223|
|piqa         |      0|acc     |0.8324|±  |0.0087|
|             |       |acc_norm|0.8379|±  |0.0086|
|winogrande   |      0|acc     |0.7569|±  |0.0121|
```
Average: 75.36

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2441|±  |0.0270|
|                              |       |acc_norm|0.2598|±  |0.0276|
|agieval_logiqa_en             |      0|acc     |0.4025|±  |0.0192|
|                              |       |acc_norm|0.3978|±  |0.0192|
|agieval_lsat_ar               |      0|acc     |0.2391|±  |0.0282|
|                              |       |acc_norm|0.2043|±  |0.0266|
|agieval_lsat_lr               |      0|acc     |0.5353|±  |0.0221|
|                              |       |acc_norm|0.5098|±  |0.0222|
|agieval_lsat_rc               |      0|acc     |0.6617|±  |0.0289|
|                              |       |acc_norm|0.5948|±  |0.0300|
|agieval_sat_en                |      0|acc     |0.7961|±  |0.0281|
|                              |       |acc_norm|0.7816|±  |0.0289|
|agieval_sat_en_without_passage|      0|acc     |0.4757|±  |0.0349|
|                              |       |acc_norm|0.4515|±  |0.0348|
|agieval_sat_math              |      0|acc     |0.4818|±  |0.0338|
|                              |       |acc_norm|0.3909|±  |0.0330|
```
Average: 44.89

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5789|±  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7154|±  |0.0235|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.5388|±  |0.0311|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.4680|±  |0.0264|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3260|±  |0.0210|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2443|±  |0.0163|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5233|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3700|±  |0.0216|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6665|±  |0.0105|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.6317|±  |0.0228|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2505|±  |0.0137|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7127|±  |0.0337|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6592|±  |0.0151|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.6860|±  |0.0147|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2200|±  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1503|±  |0.0085|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5233|±  |0.0289|
```
Average: 48.69

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3856|±  |0.0170|
|             |       |mc2   |0.5388|±  |0.0149|
```