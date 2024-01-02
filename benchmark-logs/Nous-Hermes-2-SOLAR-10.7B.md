GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5768|_  |0.0144|
|             |       |acc_norm|0.6067|_  |0.0143|
|arc_easy     |      0|acc     |0.8375|_  |0.0076|
|             |       |acc_norm|0.8316|_  |0.0077|
|boolq        |      1|acc     |0.8875|_  |0.0055|
|hellaswag    |      0|acc     |0.6467|_  |0.0048|
|             |       |acc_norm|0.8321|_  |0.0037|
|openbookqa   |      0|acc     |0.3420|_  |0.0212|
|             |       |acc_norm|0.4580|_  |0.0223|
|piqa         |      0|acc     |0.8161|_  |0.0090|
|             |       |acc_norm|0.8313|_  |0.0087|
|winogrande   |      0|acc     |0.7814|_  |0.0116|
```
Average: 74.69

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.3110|_  |0.0291|
|                              |       |acc_norm|0.3189|_  |0.0293|
|agieval_logiqa_en             |      0|acc     |0.4455|_  |0.0195|
|                              |       |acc_norm|0.4439|_  |0.0195|
|agieval_lsat_ar               |      0|acc     |0.2391|_  |0.0282|
|                              |       |acc_norm|0.2261|_  |0.0276|
|agieval_lsat_lr               |      0|acc     |0.5765|_  |0.0219|
|                              |       |acc_norm|0.5569|_  |0.0220|
|agieval_lsat_rc               |      0|acc     |0.6914|_  |0.0282|
|                              |       |acc_norm|0.6803|_  |0.0285|
|agieval_sat_en                |      0|acc     |0.8010|_  |0.0279|
|                              |       |acc_norm|0.7864|_  |0.0286|
|agieval_sat_en_without_passage|      0|acc     |0.4660|_  |0.0348|
|                              |       |acc_norm|0.4515|_  |0.0348|
|agieval_sat_math              |      0|acc     |0.4364|_  |0.0335|
|                              |       |acc_norm|0.3591|_  |0.0324|```
Average: 47.79

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.6263|_  |0.0352|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7019|_  |0.0238|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3333|_  |0.0294|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.3008|_  |0.0242|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3360|_  |0.0211|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2514|_  |0.0164|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5000|_  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3760|_  |0.0217|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.5920|_  |0.0110|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4442|_  |0.0235|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.3557|_  |0.0152|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7182|_  |0.0335|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6734|_  |0.0149|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.4630|_  |0.0158|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2328|_  |0.0120|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1657|_  |0.0089|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5000|_  |0.0289|
```
Average: 44.84

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3917|_  |0.0171|
|             |       |mc2   |0.5592|_  |0.0154|
```