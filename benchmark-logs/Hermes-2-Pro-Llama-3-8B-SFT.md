GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|                                                                                                                                                         |arc_challenge|      0|acc     |0.6425|_  |0.0140|                                                                                                                                                         |             |       |acc_norm|0.6493|_  |0.0139|                                                                                                                                                         |arc_easy     |      0|acc     |0.8813|_  |0.0066|
|             |       |acc_norm|0.8582|_  |0.0072|
|boolq        |      1|acc     |0.8719|_  |0.0058|
|hellaswag    |      0|acc     |0.6776|_  |0.0047|
|             |       |acc_norm|0.8552|_  |0.0035|
|openbookqa   |      0|acc     |0.3760|_  |0.0217|                                                                                                                                                         |             |       |acc_norm|0.4760|_  |0.0224|
|piqa         |      0|acc     |0.8275|_  |0.0088|
|             |       |acc_norm|0.8400|_  |0.0086|
|winogrande   |      0|acc     |0.8027|_  |0.0112|

```
Average: 76.48

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.3425|_  |0.0298|
|                              |       |acc_norm|0.3150|_  |0.0292|
|agieval_logiqa_en             |      0|acc     |0.4900|_  |0.0196|
|                              |       |acc_norm|0.4700|_  |0.0196|
|agieval_lsat_ar               |      0|acc     |0.2652|_  |0.0292|
|                              |       |acc_norm|0.2783|_  |0.0296|
|agieval_lsat_lr               |      0|acc     |0.7510|_  |0.0192|
|                              |       |acc_norm|0.7137|_  |0.0200|
|agieval_lsat_rc               |      0|acc     |0.7732|_  |0.0256|
|                              |       |acc_norm|0.7472|_  |0.0265|
|agieval_sat_en                |      0|acc     |0.8350|_  |0.0259|
|                              |       |acc_norm|0.8544|_  |0.0246|
|agieval_sat_en_without_passage|      0|acc     |0.5340|_  |0.0348|
|                              |       |acc_norm|0.5049|_  |0.0349|
|agieval_sat_math              |      0|acc     |0.5864|_  |0.0333|
|                              |       |acc_norm|0.4955|_  |0.0338|
```
Average: 54.74

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5842|_  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7724|_  |0.0219|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3256|_  |0.0292|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.5125|_  |0.0264|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3640|_  |0.0215|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2643|_  |0.0167|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4633|_  |0.0288|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.4980|_  |0.0224|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.8325|_  |0.0084|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.6272|_  |0.0229|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.5361|_  |0.0158|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7680|_  |0.0315|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5832|_  |0.0157|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.7990|_  |0.0127|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2208|_  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1577|_  |0.0087|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4633|_  |0.0288|
```
Average: 51.51

TruthfulQA:
Score: 56.81
