GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.6075|_  |0.0143|
|             |       |acc_norm|0.6408|_  |0.0140|
|arc_easy     |      0|acc     |0.8329|_  |0.0077|
|             |       |acc_norm|0.8152|_  |0.0080|
|boolq        |      1|acc     |0.8853|_  |0.0056|
|hellaswag    |      0|acc     |0.6868|_  |0.0046|
|             |       |acc_norm|0.8637|_  |0.0034|
|openbookqa   |      0|acc     |0.3640|_  |0.0215|
|             |       |acc_norm|0.4760|_  |0.0224|
|piqa         |      0|acc     |0.8069|_  |0.0092|
|             |       |acc_norm|0.8101|_  |0.0092|
|winogrande   |      0|acc     |0.7664|_  |0.0119|

```
Average: 75.11

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2874|_  |0.0285|
|                              |       |acc_norm|0.2913|_  |0.0286|
|agieval_logiqa_en             |      0|acc     |0.4270|_  |0.0194|
|                              |       |acc_norm|0.4270|_  |0.0194|
|agieval_lsat_ar               |      0|acc     |0.2435|_  |0.0284|
|                              |       |acc_norm|0.2348|_  |0.0280|
|agieval_lsat_lr               |      0|acc     |0.5333|_  |0.0221|
|                              |       |acc_norm|0.5353|_  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.6989|_  |0.0280|
|                              |       |acc_norm|0.6877|_  |0.0283|
|agieval_sat_en                |      0|acc     |0.7961|_  |0.0281|
|                              |       |acc_norm|0.7961|_  |0.0281|
|agieval_sat_en_without_passage|      0|acc     |0.4612|_  |0.0348|
|                              |       |acc_norm|0.4515|_  |0.0348|
|agieval_sat_math              |      0|acc     |0.3955|_  |0.0330|
|                              |       |acc_norm|0.3818|_  |0.0328|

```
Average: 47.57

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5895|_  |0.0358|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6531|_  |0.0248|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3798|_  |0.0303|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2535|_  |0.0230|
|                                                |       |exact_str_match      |0.1031|_  |0.0161|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2820|_  |0.0201|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2100|_  |0.0154|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4733|_  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.4160|_  |0.0221|
|bigbench_navigate                               |      0|multiple_choice_grade|0.6480|_  |0.0151|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.5625|_  |0.0111|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4062|_  |0.0232|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.4108|_  |0.0156|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6630|_  |0.0352|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.7120|_  |0.0144|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.6300|_  |0.0153|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2424|_  |0.0121|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1754|_  |0.0091|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4733|_  |0.0289|

```
Average: 45.45

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.5765|_  |0.0173|
|             |       |mc2   |0.7172|_  |0.0150|
```