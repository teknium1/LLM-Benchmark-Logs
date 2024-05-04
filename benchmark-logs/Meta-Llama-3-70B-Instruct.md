GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|                                                                                                                                                         |arc_challenge|      0|acc     |0.6177|_  |0.0142|                                                                                                                                                         |             |       |acc_norm|0.6459|_  |0.0140|                                                                                                                                                         |arc_easy     |      0|acc     |0.8615|_  |0.0071|
|             |       |acc_norm|0.8497|_  |0.0073|
|boolq        |      1|acc     |0.8752|_  |0.0058|
|hellaswag    |      0|acc     |0.6372|_  |0.0048|
|             |       |acc_norm|0.8253|_  |0.0038|
|openbookqa   |      0|acc     |0.3340|_  |0.0211|
|             |       |acc_norm|0.4300|_  |0.0222|
|piqa         |      0|acc     |0.8166|_  |0.0090|
|             |       |acc_norm|0.8221|_  |0.0089|
|winogrande   |      0|acc     |0.7601|_  |0.0120|

```
Average: 74.40

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.4488|_  |0.0313|
|                              |       |acc_norm|0.4370|_  |0.0312|
|agieval_logiqa_en             |      0|acc     |0.5346|_  |0.0196|
|                              |       |acc_norm|0.5300|_  |0.0196|
|agieval_lsat_ar               |      0|acc     |0.3000|_  |0.0303|
|                              |       |acc_norm|0.2870|_  |0.0299|
|agieval_lsat_lr               |      0|acc     |0.7412|_  |0.0194|
|                              |       |acc_norm|0.7196|_  |0.0199|
|agieval_lsat_rc               |      0|acc     |0.8401|_  |0.0224|
|                              |       |acc_norm|0.8253|_  |0.0232|
|agieval_sat_en                |      0|acc     |0.9126|_  |0.0197|
|                              |       |acc_norm|0.9078|_  |0.0202|
|agieval_sat_en_without_passage|      0|acc     |0.5825|_  |0.0344|
|                              |       |acc_norm|0.5534|_  |0.0347|
|agieval_sat_math              |      0|acc     |0.6591|_  |0.0320|
|                              |       |acc_norm|0.6227|_  |0.0328|
```
Average: 61.04

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.6421|_  |0.0349|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7778|_  |0.0217|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3101|_  |0.0289|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.3955|_  |0.0258|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.4820|_  |0.0224|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.3671|_  |0.0182|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.6800|_  |0.0270|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3460|_  |0.0213|
|bigbench_navigate                               |      0|multiple_choice_grade|0.6220|_  |0.0153|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.8335|_  |0.0083|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4040|_  |0.0232|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.4659|_  |0.0158|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5525|_  |0.0371|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5213|_  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.9950|_  |0.0022|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2344|_  |0.0120|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1571|_  |0.0087|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.6800|_  |0.0270|
```
Average: 52.59

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4394|_  |0.0174|
|             |       |mc2   |0.6184|_  |0.0154|
```
