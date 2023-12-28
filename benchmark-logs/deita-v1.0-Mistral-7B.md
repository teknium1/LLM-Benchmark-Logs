GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5282|±  |0.0146|
|             |       |acc_norm|0.5538|±  |0.0145|
|arc_easy     |      0|acc     |0.7900|±  |0.0084|
|             |       |acc_norm|0.7273|±  |0.0091|
|boolq        |      1|acc     |0.8410|±  |0.0064|
|hellaswag    |      0|acc     |0.6626|±  |0.0047|
|             |       |acc_norm|0.8332|±  |0.0037|
|openbookqa   |      0|acc     |0.3280|±  |0.0210|
|             |       |acc_norm|0.4580|±  |0.0223|
|piqa         |      0|acc     |0.7938|±  |0.0094|
|             |       |acc_norm|0.7922|±  |0.0095|
|winogrande   |      0|acc     |0.7490|±  |0.0122|
```
Average: 70.78

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2244|±  |0.0262|
|                              |       |acc_norm|0.2323|±  |0.0265|
|agieval_logiqa_en             |      0|acc     |0.3410|±  |0.0186|
|                              |       |acc_norm|0.3364|±  |0.0185|
|agieval_lsat_ar               |      0|acc     |0.2391|±  |0.0282|
|                              |       |acc_norm|0.2609|±  |0.0290|
|agieval_lsat_lr               |      0|acc     |0.3824|±  |0.0215|
|                              |       |acc_norm|0.3882|±  |0.0216|
|agieval_lsat_rc               |      0|acc     |0.5576|±  |0.0303|
|                              |       |acc_norm|0.5502|±  |0.0304|
|agieval_sat_en                |      0|acc     |0.6505|±  |0.0333|
|                              |       |acc_norm|0.6408|±  |0.0335|
|agieval_sat_en_without_passage|      0|acc     |0.4369|±  |0.0346|
|                              |       |acc_norm|0.4320|±  |0.0346|
|agieval_sat_math              |      0|acc     |0.3409|±  |0.0320|
|                              |       |acc_norm|0.3227|±  |0.0316|
```
Average: 39.54

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5842|±  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6396|±  |0.0250|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3333|±  |0.0294|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1086|±  |0.0164|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2880|±  |0.0203|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1686|±  |0.0142|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4300|±  |0.0286|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3100|±  |0.0207|
|bigbench_navigate                               |      0|multiple_choice_grade|0.4980|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.4875|±  |0.0112|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3237|±  |0.0221|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2154|±  |0.0130|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6575|±  |0.0354|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5639|±  |0.0158|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2500|±  |0.0137|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2256|±  |0.0118|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1794|±  |0.0092|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4300|±  |0.0286|
```
Average: 37.19

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.5288|±  |0.0175|
|             |       |mc2   |0.6715|±  |0.0158|
```