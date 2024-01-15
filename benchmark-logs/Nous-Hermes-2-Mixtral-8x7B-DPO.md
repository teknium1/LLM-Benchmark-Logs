GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5990|±  |0.0143|
|             |       |acc_norm|0.6425|±  |0.0140|
|arc_easy     |      0|acc     |0.8657|±  |0.0070|
|             |       |acc_norm|0.8636|±  |0.0070|
|boolq        |      1|acc     |0.8783|±  |0.0057|
|hellaswag    |      0|acc     |0.6661|±  |0.0047|
|             |       |acc_norm|0.8489|±  |0.0036|
|openbookqa   |      0|acc     |0.3440|±  |0.0213|
|             |       |acc_norm|0.4660|±  |0.0223|
|piqa         |      0|acc     |0.8324|±  |0.0087|
|             |       |acc_norm|0.8379|±  |0.0086|
|winogrande   |      0|acc     |0.7616|±  |0.0120|
```
Average: 75.70

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2402|±  |0.0269|
|                              |       |acc_norm|0.2520|±  |0.0273|
|agieval_logiqa_en             |      0|acc     |0.4117|±  |0.0193|
|                              |       |acc_norm|0.4055|±  |0.0193|
|agieval_lsat_ar               |      0|acc     |0.2348|±  |0.0280|
|                              |       |acc_norm|0.2087|±  |0.0269|
|agieval_lsat_lr               |      0|acc     |0.5549|±  |0.0220|
|                              |       |acc_norm|0.5294|±  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.6617|±  |0.0289|
|                              |       |acc_norm|0.6357|±  |0.0294|
|agieval_sat_en                |      0|acc     |0.8010|±  |0.0279|
|                              |       |acc_norm|0.7913|±  |0.0284|
|agieval_sat_en_without_passage|      0|acc     |0.4806|±  |0.0349|
|                              |       |acc_norm|0.4612|±  |0.0348|
|agieval_sat_math              |      0|acc     |0.4909|±  |0.0338|
|                              |       |acc_norm|0.4000|±  |0.0331|
```
Average: 46.05

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.6105|±  |0.0355|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7182|±  |0.0235|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.5736|±  |0.0308|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.4596|±  |0.0263|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3500|±  |0.0214|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2500|±  |0.0164|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5200|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3540|±  |0.0214|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6900|±  |0.0103|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.6317|±  |0.0228|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2535|±  |0.0138|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7293|±  |0.0331|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6744|±  |0.0149|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.7400|±  |0.0139|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2176|±  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1543|±  |0.0086|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5200|±  |0.0289|
```
Average: 49.70

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4162|±  |0.0173|
|             |       |mc2   |0.5783|±  |0.0151|
```