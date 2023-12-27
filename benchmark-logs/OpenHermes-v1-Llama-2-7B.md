GPT4All:
```

```
Average: 

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2441|±  |0.0270|
|                              |       |acc_norm|0.2402|±  |0.0269|
|agieval_logiqa_en             |      0|acc     |0.2458|±  |0.0169|
|                              |       |acc_norm|0.2965|±  |0.0179|
|agieval_lsat_ar               |      0|acc     |0.2522|±  |0.0287|
|                              |       |acc_norm|0.2130|±  |0.0271|
|agieval_lsat_lr               |      0|acc     |0.2745|±  |0.0198|
|                              |       |acc_norm|0.2686|±  |0.0196|
|agieval_lsat_rc               |      0|acc     |0.2900|±  |0.0277|
|                              |       |acc_norm|0.2379|±  |0.0260|
|agieval_sat_en                |      0|acc     |0.4466|±  |0.0347|
|                              |       |acc_norm|0.3738|±  |0.0338|
|agieval_sat_en_without_passage|      0|acc     |0.3738|±  |0.0338|
|                              |       |acc_norm|0.3301|±  |0.0328|
|agieval_sat_math              |      0|acc     |0.2318|±  |0.0285|
|                              |       |acc_norm|0.1864|±  |0.0263|
```
Average: 26.83

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5000|±  |0.0364|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.5908|±  |0.0256|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3023|±  |0.0286|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1003|±  |0.0159|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2520|±  |0.0194|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1871|±  |0.0148|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.3833|±  |0.0281|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.2500|±  |0.0194|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.4370|±  |0.0111|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.2679|±  |0.0209|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2495|±  |0.0137|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5249|±  |0.0372|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5406|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2470|±  |0.0136|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.1944|±  |0.0112|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1509|±  |0.0086|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.3833|±  |0.0281|
```
Average: 33.67

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.2999|±  |0.0160|
|             |       |mc2   |0.4542|±  |0.0148|
```