GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5529|±  |0.0145|
|             |       |acc_norm|0.5870|±  |0.0144|
|arc_easy     |      0|acc     |0.8371|±  |0.0076|
|             |       |acc_norm|0.8144|±  |0.0080|
|boolq        |      1|acc     |0.8599|±  |0.0061|
|hellaswag    |      0|acc     |0.6133|±  |0.0049|
|             |       |acc_norm|0.7989|±  |0.0040|
|openbookqa   |      0|acc     |0.3940|±  |0.0219|
|             |       |acc_norm|0.4680|±  |0.0223|
|piqa         |      0|acc     |0.8063|±  |0.0092|
|             |       |acc_norm|0.8156|±  |0.0090|
|winogrande   |      0|acc     |0.7372|±  |0.0124|
```
Average: 72.59

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2441|±  |0.0270|
|                              |       |acc_norm|0.2441|±  |0.0270|
|agieval_logiqa_en             |      0|acc     |0.3687|±  |0.0189|
|                              |       |acc_norm|0.3840|±  |0.0191|
|agieval_lsat_ar               |      0|acc     |0.2304|±  |0.0278|
|                              |       |acc_norm|0.2174|±  |0.0273|
|agieval_lsat_lr               |      0|acc     |0.5471|±  |0.0221|
|                              |       |acc_norm|0.5373|±  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.6617|±  |0.0289|
|                              |       |acc_norm|0.6357|±  |0.0294|
|agieval_sat_en                |      0|acc     |0.7670|±  |0.0295|
|                              |       |acc_norm|0.7379|±  |0.0307|
|agieval_sat_en_without_passage|      0|acc     |0.4417|±  |0.0347|
|                              |       |acc_norm|0.4223|±  |0.0345|
|agieval_sat_math              |      0|acc     |0.4000|±  |0.0331|
|                              |       |acc_norm|0.3455|±  |0.0321|
```
Average: 44.05

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.6000|±  |0.0356|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6585|±  |0.0247|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3178|±  |0.0290|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.2340|±  |0.0224|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2980|±  |0.0205|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2057|±  |0.0153|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5367|±  |0.0288|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.4040|±  |0.0220|
|bigbench_navigate                               |      0|multiple_choice_grade|0.4970|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.7075|±  |0.0102|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4821|±  |0.0236|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2295|±  |0.0133|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6906|±  |0.0345|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5375|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.6270|±  |0.0153|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2216|±  |0.0118|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1594|±  |0.0088|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5367|±  |0.0288|
```
Average: 44.13

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3929|±  |0.0171|
|             |       |mc2   |0.5633|±  |0.0154|
```
