GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.2705|±  |0.0130|
|             |       |acc_norm|0.3183|±  |0.0136|
|arc_easy     |      0|acc     |0.6124|±  |0.0100|
|             |       |acc_norm|0.5678|±  |0.0102|
|boolq        |      1|acc     |0.6324|±  |0.0084|
|hellaswag    |      0|acc     |0.4492|±  |0.0050|
|             |       |acc_norm|0.5896|±  |0.0049|
|openbookqa   |      0|acc     |0.2420|±  |0.0192|
|             |       |acc_norm|0.3440|±  |0.0213|
|piqa         |      0|acc     |0.7301|±  |0.0104|
|             |       |acc_norm|0.7301|±  |0.0104|
|winogrande   |      0|acc     |0.5864|±  |0.0138|
```
Average: 53.84

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.1457|±  |0.0222|
|                              |       |acc_norm|0.1535|±  |0.0227|
|agieval_logiqa_en             |      0|acc     |0.2350|±  |0.0166|
|                              |       |acc_norm|0.3088|±  |0.0181|
|agieval_lsat_ar               |      0|acc     |0.1913|±  |0.0260|
|                              |       |acc_norm|0.1870|±  |0.0258|
|agieval_lsat_lr               |      0|acc     |0.1961|±  |0.0176|
|                              |       |acc_norm|0.2196|±  |0.0183|
|agieval_lsat_rc               |      0|acc     |0.2007|±  |0.0245|
|                              |       |acc_norm|0.1784|±  |0.0234|
|agieval_sat_en                |      0|acc     |0.2282|±  |0.0293|
|                              |       |acc_norm|0.2233|±  |0.0291|
|agieval_sat_en_without_passage|      0|acc     |0.1893|±  |0.0274|
|                              |       |acc_norm|0.2136|±  |0.0286|
|agieval_sat_math              |      0|acc     |0.2591|±  |0.0296|
|                              |       |acc_norm|0.2318|±  |0.0285|
```
Average: 21.45

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.4895|±  |0.0364|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.4878|±  |0.0261|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3527|±  |0.0298|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.0446|±  |0.0109|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2180|±  |0.0185|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1457|±  |0.0133|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.3633|±  |0.0278|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3780|±  |0.0217|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.2980|±  |0.0102|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3036|±  |0.0217|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.1533|±  |0.0114|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5249|±  |0.0372|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.4980|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2780|±  |0.0142|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.1848|±  |0.0110|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1274|±  |0.0080|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.3633|±  |0.0278|
```
Average: 31.73

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.2130|±  |0.0143|
|             |       |mc2   |0.3707|±  |0.0138|
```