GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5623|±  |0.0145|
|             |       |acc_norm|0.6007|±  |0.0143|
|arc_easy     |      0|acc     |0.8346|±  |0.0076|
|             |       |acc_norm|0.8165|±  |0.0079|
|boolq        |      1|acc     |0.8657|±  |0.0060|
|hellaswag    |      0|acc     |0.6310|±  |0.0048|
|             |       |acc_norm|0.8173|±  |0.0039|
|openbookqa   |      0|acc     |0.3460|±  |0.0213|
|             |       |acc_norm|0.4480|±  |0.0223|
|piqa         |      0|acc     |0.8145|±  |0.0091|
|             |       |acc_norm|0.8270|±  |0.0088|
|winogrande   |      0|acc     |0.7435|±  |0.0123|
```
Average: 73.12

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2323|±  |0.0265|
|                              |       |acc_norm|0.2362|±  |0.0267|
|agieval_logiqa_en             |      0|acc     |0.3871|±  |0.0191|
|                              |       |acc_norm|0.3948|±  |0.0192|
|agieval_lsat_ar               |      0|acc     |0.2522|±  |0.0287|
|                              |       |acc_norm|0.2304|±  |0.0278|
|agieval_lsat_lr               |      0|acc     |0.5059|±  |0.0222|
|                              |       |acc_norm|0.5157|±  |0.0222|
|agieval_lsat_rc               |      0|acc     |0.5911|±  |0.0300|
|                              |       |acc_norm|0.5725|±  |0.0302|
|agieval_sat_en                |      0|acc     |0.7476|±  |0.0303|
|                              |       |acc_norm|0.7330|±  |0.0309|
|agieval_sat_en_without_passage|      0|acc     |0.4417|±  |0.0347|
|                              |       |acc_norm|0.4126|±  |0.0344|
|agieval_sat_math              |      0|acc     |0.3773|±  |0.0328|
|                              |       |acc_norm|0.3500|±  |0.0322|
```
Average: 43.07

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5316|±  |0.0363|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6667|±  |0.0246|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3411|±  |0.0296|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2145|±  |0.0217|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2860|±  |0.0202|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2086|±  |0.0154|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4800|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3620|±  |0.0215|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6630|±  |0.0106|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4241|±  |0.0234|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2285|±  |0.0133|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6796|±  |0.0348|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6491|±  |0.0152|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2800|±  |0.0142|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2072|±  |0.0115|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1691|±  |0.0090|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4800|±  |0.0289|
```
Average: 40.96

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3599|±  |0.0168|
|             |       |mc2   |0.5304|±  |0.0153|
```