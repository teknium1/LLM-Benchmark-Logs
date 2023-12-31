GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.2782|±  |0.0131|
|             |       |acc_norm|0.3012|±  |0.0134|
|arc_easy     |      0|acc     |0.6031|±  |0.0100|
|             |       |acc_norm|0.5535|±  |0.0102|
|boolq        |      1|acc     |0.5774|±  |0.0086|
|hellaswag    |      0|acc     |0.4499|±  |0.0050|
|             |       |acc_norm|0.5917|±  |0.0049|
|openbookqa   |      0|acc     |0.2180|±  |0.0185|
|             |       |acc_norm|0.3600|±  |0.0215|
|piqa         |      0|acc     |0.7334|±  |0.0103|
|             |       |acc_norm|0.7318|±  |0.0103|
|winogrande   |      0|acc     |0.5935|±  |0.0138|
```
Average: 52.99

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.1575|±  |0.0229|
|                              |       |acc_norm|0.1693|±  |0.0236|
|agieval_logiqa_en             |      0|acc     |0.2488|±  |0.0170|
|                              |       |acc_norm|0.2934|±  |0.0179|
|agieval_lsat_ar               |      0|acc     |0.2304|±  |0.0278|
|                              |       |acc_norm|0.2043|±  |0.0266|
|agieval_lsat_lr               |      0|acc     |0.2059|±  |0.0179|
|                              |       |acc_norm|0.2353|±  |0.0188|
|agieval_lsat_rc               |      0|acc     |0.1970|±  |0.0243|
|                              |       |acc_norm|0.1710|±  |0.0230|
|agieval_sat_en                |      0|acc     |0.2427|±  |0.0299|
|                              |       |acc_norm|0.1893|±  |0.0274|
|agieval_sat_en_without_passage|      0|acc     |0.2136|±  |0.0286|
|                              |       |acc_norm|0.1942|±  |0.0276|
|agieval_sat_math              |      0|acc     |0.3045|±  |0.0311|
|                              |       |acc_norm|0.2273|±  |0.0283|
```
Average: 21.05

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5053|±  |0.0364|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.4851|±  |0.0261|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.2984|±  |0.0285|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.0474|±  |0.0112|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2100|±  |0.0182|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1471|±  |0.0134|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.3667|±  |0.0279|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3440|±  |0.0213|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.3105|±  |0.0103|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3013|±  |0.0217|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2295|±  |0.0133|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5138|±  |0.0373|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.4970|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2940|±  |0.0144|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.1976|±  |0.0113|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1371|±  |0.0082|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.3667|±  |0.0279|
```
Average: 31.95

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.2203|±  |0.0145|
|             |       |mc2   |0.3759|±  |0.0138|
```