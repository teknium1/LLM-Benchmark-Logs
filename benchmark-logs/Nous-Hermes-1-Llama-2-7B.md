GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.4735|±  |0.0146|
|             |       |acc_norm|0.5017|±  |0.0146|
|arc_easy     |      0|acc     |0.7946|±  |0.0083|
|             |       |acc_norm|0.7605|±  |0.0088|
|boolq        |      1|acc     |0.8000|±  |0.0070|
|hellaswag    |      0|acc     |0.5924|±  |0.0049|
|             |       |acc_norm|0.7774|±  |0.0042|
|openbookqa   |      0|acc     |0.3600|±  |0.0215|
|             |       |acc_norm|0.4660|±  |0.0223|
|piqa         |      0|acc     |0.7889|±  |0.0095|
|             |       |acc_norm|0.7976|±  |0.0094|
|winogrande   |      0|acc     |0.6993|±  |0.0129|
```
Average: 68.60

AGIEval:
```

```
Average: 

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5579|±  |0.0361|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6233|±  |0.0253|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3062|±  |0.0288|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2006|±  |0.0212|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2540|±  |0.0195|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1657|±  |0.0141|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4067|±  |0.0284|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.2780|±  |0.0201|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.4405|±  |0.0111|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.2701|±  |0.0210|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2034|±  |0.0127|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5028|±  |0.0373|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6136|±  |0.0155|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2720|±  |0.0141|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.1944|±  |0.0112|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1497|±  |0.0085|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4067|±  |0.0284|
```
Average: 35.25

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3341|±  |0.0165|
|             |       |mc2   |0.4910|±  |0.0151|
```