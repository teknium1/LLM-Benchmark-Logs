GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5503|_  |0.0145|
|             |       |acc_norm|0.5828|_  |0.0144|
|arc_easy     |      0|acc     |0.8333|_  |0.0076|
|             |       |acc_norm|0.8144|_  |0.0080|
|boolq        |      1|acc     |0.8590|_  |0.0061|
|hellaswag    |      0|acc     |0.6260|_  |0.0048|
|             |       |acc_norm|0.8054|_  |0.0040|
|openbookqa   |      0|acc     |0.3800|_  |0.0217|
|             |       |acc_norm|0.4560|_  |0.0223|
|piqa         |      0|acc     |0.7987|_  |0.0094|
|             |       |acc_norm|0.8118|_  |0.0091|
|winogrande   |      0|acc     |0.7514|_  |0.0121|
```
Average: 72.58

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2520|_  |0.0273|
|                              |       |acc_norm|0.2480|_  |0.0272|
|agieval_logiqa_en             |      0|acc     |0.3564|_  |0.0188|
|                              |       |acc_norm|0.3656|_  |0.0189|
|agieval_lsat_ar               |      0|acc     |0.1870|_  |0.0258|
|                              |       |acc_norm|0.1957|_  |0.0262|
|agieval_lsat_lr               |      0|acc     |0.5608|_  |0.0220|
|                              |       |acc_norm|0.5314|_  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.6320|_  |0.0295|
|                              |       |acc_norm|0.6171|_  |0.0297|
|agieval_sat_en                |      0|acc     |0.7379|_  |0.0307|
|                              |       |acc_norm|0.7039|_  |0.0319|
|agieval_sat_en_without_passage|      0|acc     |0.4029|_  |0.0343|
|                              |       |acc_norm|0.3641|_  |0.0336|
|agieval_sat_math              |      0|acc     |0.3818|_  |0.0328|
|                              |       |acc_norm|0.3727|_  |0.0327|
```
Average: 42.48

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5737|±  |0.0360|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6667|±  |0.0246|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3178|±  |0.0290|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1755|±  |0.0201|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3120|±  |0.0207|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2014|±  |0.0152|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5500|±  |0.0288|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.4300|±  |0.0222|
|bigbench_navigate                               |      0|multiple_choice_grade|0.4980|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.7010|±  |0.0102|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4688|±  |0.0236|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.1974|±  |0.0126|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7403|±  |0.0327|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5426|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.5320|±  |0.0158|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2280|±  |0.0119|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1531|±  |0.0086|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5500|±  |0.0288|
```
Average: 43.55

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4076|_  |0.0172|
|             |       |mc2   |0.5788|_  |0.0157|
```
