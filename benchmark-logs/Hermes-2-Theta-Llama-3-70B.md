GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.6638|_  |0.0138|
|             |       |acc_norm|0.6903|_  |0.0135|
|arc_easy     |      0|acc     |0.8851|_  |0.0065|
|             |       |acc_norm|0.8712|_  |0.0069|
|boolq        |      1|acc     |0.8820|_  |0.0056|
|hellaswag    |      0|acc     |0.6579|_  |0.0047|
|             |       |acc_norm|0.8432|_  |0.0036|
|openbookqa   |      0|acc     |0.3920|_  |0.0219|
|             |       |acc_norm|0.4740|_  |0.0224|
|piqa         |      0|acc     |0.8286|_  |0.0088|
|             |       |acc_norm|0.8351|_  |0.0087|
|winogrande   |      0|acc     |0.7893|_  |0.0115|
```
Average: 76.93

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.4055|_  |0.0309|
|                              |       |acc_norm|0.4094|_  |0.0309|
|agieval_logiqa_en             |      0|acc     |0.5100|_  |0.0196|
|                              |       |acc_norm|0.5023|_  |0.0196|
|agieval_lsat_ar               |      0|acc     |0.2783|_  |0.0296|
|                              |       |acc_norm|0.2957|_  |0.0302|
|agieval_lsat_lr               |      0|acc     |0.7451|_  |0.0193|
|                              |       |acc_norm|0.7333|_  |0.0196|
|agieval_lsat_rc               |      0|acc     |0.8290|_  |0.0230|
|                              |       |acc_norm|0.8104|_  |0.0239|
|agieval_sat_en                |      0|acc     |0.9029|_  |0.0207|
|                              |       |acc_norm|0.9029|_  |0.0207|
|agieval_sat_en_without_passage|      0|acc     |0.5825|_  |0.0344|
|                              |       |acc_norm|0.5631|_  |0.0346|
|agieval_sat_math              |      0|acc     |0.6318|_  |0.0326|
|                              |       |acc_norm|0.6227|_  |0.0328|
```
Average: 60.50

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.6737|_  |0.0341|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7724|_  |0.0219|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3256|_  |0.0292|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.4763|_  |0.0264|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.4720|_  |0.0223|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.3486|_  |0.0180|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.6367|_  |0.0278|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.5220|_  |0.0224|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5930|_  |0.0155|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.8600|_  |0.0078|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.7411|_  |0.0207|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.5281|_  |0.0158|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6961|_  |0.0343|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5751|_  |0.0158|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.9880|_  |0.0034|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2296|_  |0.0119|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1691|_  |0.0090|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.6367|_  |0.0278|
```
Average: 56.91

TruthfulQA:
```|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4565|_  |0.0174|
|             |       |mc2   |0.6288|_  |0.0151|
```
62.88

IFEval:
87.99

MTBench:
First Turn  - 9.1625
Second Turn - 8.925
Average     - 9.04375