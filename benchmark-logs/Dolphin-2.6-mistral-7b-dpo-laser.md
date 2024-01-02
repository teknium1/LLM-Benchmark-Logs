GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5640|±  |0.0145|
|             |       |acc_norm|0.5887|±  |0.0144|
|arc_easy     |      0|acc     |0.8392|±  |0.0075|
|             |       |acc_norm|0.8026|±  |0.0082|
|boolq        |      1|acc     |0.8731|±  |0.0058|
|hellaswag    |      0|acc     |0.6476|±  |0.0048|
|             |       |acc_norm|0.8364|±  |0.0037|
|openbookqa   |      0|acc     |0.3460|±  |0.0213|
|             |       |acc_norm|0.4700|±  |0.0223|
|piqa         |      0|acc     |0.8215|±  |0.0089|
|             |       |acc_norm|0.8324|±  |0.0087|
|winogrande   |      0|acc     |0.7624|±  |0.0120|
```
Average: 73.79

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2047|±  |0.0254|
|                              |       |acc_norm|0.1969|±  |0.0250|
|agieval_logiqa_en             |      0|acc     |0.3364|±  |0.0185|
|                              |       |acc_norm|0.3410|±  |0.0186|
|agieval_lsat_ar               |      0|acc     |0.2217|±  |0.0275|
|                              |       |acc_norm|0.2087|±  |0.0269|
|agieval_lsat_lr               |      0|acc     |0.3902|±  |0.0216|
|                              |       |acc_norm|0.3961|±  |0.0217|
|agieval_lsat_rc               |      0|acc     |0.5353|±  |0.0305|
|                              |       |acc_norm|0.5130|±  |0.0305|
|agieval_sat_en                |      0|acc     |0.6990|±  |0.0320|
|                              |       |acc_norm|0.6893|±  |0.0323|
|agieval_sat_en_without_passage|      0|acc     |0.4029|±  |0.0343|
|                              |       |acc_norm|0.3981|±  |0.0342|
|agieval_sat_math              |      0|acc     |0.3864|±  |0.0329|
|                              |       |acc_norm|0.3409|±  |0.0320|
```
Average: 38.55

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5842|±  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6829|±  |0.0243|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3488|±  |0.0297|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2033|±  |0.0213|
|                                                |       |exact_str_match      |0.0306|±  |0.0091|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2680|±  |0.0198|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2086|±  |0.0154|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4967|±  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.5140|±  |0.0224|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5330|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6715|±  |0.0105|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3996|±  |0.0232|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.1283|±  |0.0106|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6575|±  |0.0354|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.7160|±  |0.0144|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.3680|±  |0.0153|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2296|±  |0.0119|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1663|±  |0.0089|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4967|±  |0.0289|
```
Average: 42.63

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4431|±  |0.0174|
|             |       |mc2   |0.6106|±  |0.0151|
```