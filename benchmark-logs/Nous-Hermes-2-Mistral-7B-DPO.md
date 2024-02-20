GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5776|±  |0.0144|
|             |       |acc_norm|0.6220|±  |0.0142|
|arc_easy     |      0|acc     |0.8380|±  |0.0076|
|             |       |acc_norm|0.8245|±  |0.0078|
|boolq        |      1|acc     |0.8624|±  |0.0060|
|hellaswag    |      0|acc     |0.6418|±  |0.0048|
|             |       |acc_norm|0.8249|±  |0.0038|
|openbookqa   |      0|acc     |0.3420|±  |0.0212|
|             |       |acc_norm|0.4540|±  |0.0223|
|piqa         |      0|acc     |0.8177|±  |0.0090|
|             |       |acc_norm|0.8264|±  |0.0088|
|winogrande   |      0|acc     |0.7466|±  |0.0122|
```
Average: 73.72

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2047|±  |0.0254|
|                              |       |acc_norm|0.2283|±  |0.0264|
|agieval_logiqa_en             |      0|acc     |0.3779|±  |0.0190|
|                              |       |acc_norm|0.3932|±  |0.0192|
|agieval_lsat_ar               |      0|acc     |0.2652|±  |0.0292|
|                              |       |acc_norm|0.2522|±  |0.0287|
|agieval_lsat_lr               |      0|acc     |0.5216|±  |0.0221|
|                              |       |acc_norm|0.5137|±  |0.0222|
|agieval_lsat_rc               |      0|acc     |0.5911|±  |0.0300|
|                              |       |acc_norm|0.5836|±  |0.0301|
|agieval_sat_en                |      0|acc     |0.7427|±  |0.0305|
|                              |       |acc_norm|0.7184|±  |0.0314|
|agieval_sat_en_without_passage|      0|acc     |0.4612|±  |0.0348|
|                              |       |acc_norm|0.4466|±  |0.0347|
|agieval_sat_math              |      0|acc     |0.3818|±  |0.0328|
|                              |       |acc_norm|0.3545|±  |0.0323|
```
Average: 43.63

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5579|±  |0.0361|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6694|±  |0.0245|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3333|±  |0.0294|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2061|±  |0.0214|
|                                                |       |exact_str_match      |0.2256|±  |0.0221|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3120|±  |0.0207|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2114|±  |0.0154|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4900|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3600|±  |0.0215|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6660|±  |0.0105|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4420|±  |0.0235|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2766|±  |0.0142|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6630|±  |0.0352|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6653|±  |0.0150|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.3190|±  |0.0147|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2128|±  |0.0116|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1737|±  |0.0091|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4900|±  |0.0289|
```
Average: 41.94

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3892|±  |0.0171|
|             |       |mc2   |0.5642|±  |0.0153|
```
