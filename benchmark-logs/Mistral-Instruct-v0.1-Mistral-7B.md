GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5017|±  |0.0146|
|             |       |acc_norm|0.5213|±  |0.0146|
|arc_easy     |      0|acc     |0.8005|±  |0.0082|
|             |       |acc_norm|0.7681|±  |0.0087|
|boolq        |      1|acc     |0.8028|±  |0.0070|
|hellaswag    |      0|acc     |0.5629|±  |0.0050|
|             |       |acc_norm|0.7464|±  |0.0043|
|openbookqa   |      0|acc     |0.3260|±  |0.0210|
|             |       |acc_norm|0.4320|±  |0.0222|
|piqa         |      0|acc     |0.7938|±  |0.0094|
|             |       |acc_norm|0.7905|±  |0.0095|
|winogrande   |      0|acc     |0.6953|±  |0.0129|
```
Average: 67.95

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.1969|±  |0.0250|
|                              |       |acc_norm|0.1969|±  |0.0250|
|agieval_logiqa_en             |      0|acc     |0.3118|±  |0.0182|
|                              |       |acc_norm|0.3364|±  |0.0185|
|agieval_lsat_ar               |      0|acc     |0.2217|±  |0.0275|
|                              |       |acc_norm|0.2304|±  |0.0278|
|agieval_lsat_lr               |      0|acc     |0.3686|±  |0.0214|
|                              |       |acc_norm|0.3706|±  |0.0214|
|agieval_lsat_rc               |      0|acc     |0.4758|±  |0.0305|
|                              |       |acc_norm|0.4238|±  |0.0302|
|agieval_sat_en                |      0|acc     |0.5583|±  |0.0347|
|                              |       |acc_norm|0.5437|±  |0.0348|
|agieval_sat_en_without_passage|      0|acc     |0.3544|±  |0.0334|
|                              |       |acc_norm|0.3155|±  |0.0325|
|agieval_sat_math              |      0|acc     |0.2773|±  |0.0302|
|                              |       |acc_norm|0.2591|±  |0.0296|
```
Average: 33.46

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5263|±  |0.0363|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6640|±  |0.0246|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3566|±  |0.0299|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1003|±  |0.0159|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2400|±  |0.0191|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1714|±  |0.0143|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.3633|±  |0.0278|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3260|±  |0.0210|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.4520|±  |0.0111|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3281|±  |0.0222|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2044|±  |0.0128|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5414|±  |0.0371|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.4970|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2720|±  |0.0141|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2280|±  |0.0119|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1514|±  |0.0086|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.3633|±  |0.0278|
```
Average: 34.92

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3917|±  |0.0171|
|             |       |mc2   |0.5592|±  |0.0153|
```