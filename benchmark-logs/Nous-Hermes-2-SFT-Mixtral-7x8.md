GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5956|_  |0.0143|
|             |       |acc_norm|0.6331|_  |0.0141|
|arc_easy     |      0|acc     |0.8598|_  |0.0071|
|             |       |acc_norm|0.8594|_  |0.0071|
|boolq        |      1|acc     |0.8783|_  |0.0057|
|hellaswag    |      0|acc     |0.6599|_  |0.0047|
|             |       |acc_norm|0.8433|_  |0.0036|
|openbookqa   |      0|acc     |0.3380|_  |0.0212|
|             |       |acc_norm|0.4640|_  |0.0223|
|piqa         |      0|acc     |0.8330|_  |0.0087|
|             |       |acc_norm|0.8384|_  |0.0086|
|winogrande   |      0|acc     |0.7506|_  |0.0122|

```
Average: 75.24

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2441|_  |0.0270|
|                              |       |acc_norm|0.2559|_  |0.0274|
|agieval_logiqa_en             |      0|acc     |0.4025|_  |0.0192|
|                              |       |acc_norm|0.4101|_  |0.0193|
|agieval_lsat_ar               |      0|acc     |0.2304|_  |0.0278|
|                              |       |acc_norm|0.1913|_  |0.0260|
|agieval_lsat_lr               |      0|acc     |0.5392|_  |0.0221|
|                              |       |acc_norm|0.5098|_  |0.0222|
|agieval_lsat_rc               |      0|acc     |0.6468|_  |0.0292|
|                              |       |acc_norm|0.5985|_  |0.0299|
|agieval_sat_en                |      0|acc     |0.8058|_  |0.0276|
|                              |       |acc_norm|0.7718|_  |0.0293|
|agieval_sat_en_without_passage|      0|acc     |0.4806|_  |0.0349|
|                              |       |acc_norm|0.4466|_  |0.0347|
|agieval_sat_math              |      0|acc     |0.4909|_  |0.0338|
|                              |       |acc_norm|0.4000|_  |0.0331|

```
Average: 44.80

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5789|_  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7127|_  |0.0236|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.5426|_  |0.0311|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.4735|_  |0.0264|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3280|_  |0.0210|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2471|_  |0.0163|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.5233|_  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3680|_  |0.0216|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6685|_  |0.0105|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.6362|_  |0.0228|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2505|_  |0.0137|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7072|_  |0.0339|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6613|_  |0.0151|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.6840|_  |0.0147|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2208|_  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1474|_  |0.0085|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.5233|_  |0.0289|

```
Average: 48.74

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3905|_  |0.0171|
|             |       |mc2   |0.5385|_  |0.0149|
```