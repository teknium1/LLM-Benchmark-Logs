GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5179|±  |0.0146|
|             |       |acc_norm|0.5512|±  |0.0145|
|arc_easy     |      0|acc     |0.8178|±  |0.0079|
|             |       |acc_norm|0.7971|±  |0.0083|
|boolq        |      1|acc     |0.8407|±  |0.0064|
|hellaswag    |      0|acc     |0.5908|±  |0.0049|
|             |       |acc_norm|0.7924|±  |0.0040|
|openbookqa   |      0|acc     |0.3340|±  |0.0211|
|             |       |acc_norm|0.4320|±  |0.0222|
|piqa         |      0|acc     |0.8003|±  |0.0093|
|             |       |acc_norm|0.8101|±  |0.0092|
|winogrande   |      0|acc     |0.7395|±  |0.0123|
```
Average: 70.90

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2953|±  |0.0287|
|                              |       |acc_norm|0.2598|±  |0.0276|
|agieval_logiqa_en             |      0|acc     |0.3748|±  |0.0190|
|                              |       |acc_norm|0.3825|±  |0.0191|
|agieval_lsat_ar               |      0|acc     |0.2087|±  |0.0269|
|                              |       |acc_norm|0.2000|±  |0.0264|
|agieval_lsat_lr               |      0|acc     |0.4588|±  |0.0221|
|                              |       |acc_norm|0.4176|±  |0.0219|
|agieval_lsat_rc               |      0|acc     |0.6283|±  |0.0295|
|                              |       |acc_norm|0.5613|±  |0.0303|
|agieval_sat_en                |      0|acc     |0.7816|±  |0.0289|
|                              |       |acc_norm|0.7039|±  |0.0319|
|agieval_sat_en_without_passage|      0|acc     |0.3883|±  |0.0340|
|                              |       |acc_norm|0.3641|±  |0.0336|
|agieval_sat_math              |      0|acc     |0.4182|±  |0.0333|
|                              |       |acc_norm|0.3500|±  |0.0322|
```
Average: 40.49

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5053|±  |0.0364|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7154|±  |0.0235|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.2984|±  |0.0285|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.3287|±  |0.0248|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2980|±  |0.0205|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2286|±  |0.0159|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5700|±  |0.0286|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3260|±  |0.0210|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5760|±  |0.0156|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6325|±  |0.0108|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4754|±  |0.0236|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.3216|±  |0.0148|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6685|±  |0.0351|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5030|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.6000|±  |0.0155|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2168|±  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1697|±  |0.0090|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5700|±  |0.0286|
```
Average: 44.46

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3672|±  |0.0169|
|             |       |mc2   |0.5399|±  |0.0150|
```
