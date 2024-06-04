GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5452|±  |0.0146|
|             |       |acc_norm|0.5700|±  |0.0145|
|arc_easy     |      0|acc     |0.8363|±  |0.0076|
|             |       |acc_norm|0.8114|±  |0.0080|
|boolq        |      1|acc     |0.8673|±  |0.0059|
|hellaswag    |      0|acc     |0.6200|±  |0.0048|
|             |       |acc_norm|0.8107|±  |0.0039|
|openbookqa   |      0|acc     |0.3500|±  |0.0214|
|             |       |acc_norm|0.4580|±  |0.0223|
|piqa         |      0|acc     |0.8085|±  |0.0092|
|             |       |acc_norm|0.8243|±  |0.0089|
|winogrande   |      0|acc     |0.7459|±  |0.0122|
```
Average: 72.68

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2283|±  |0.0264|
|                              |       |acc_norm|0.2283|±  |0.0264|
|agieval_logiqa_en             |      0|acc     |0.3594|±  |0.0188|
|                              |       |acc_norm|0.3671|±  |0.0189|
|agieval_lsat_ar               |      0|acc     |0.2217|±  |0.0275|
|                              |       |acc_norm|0.2217|±  |0.0275|
|agieval_lsat_lr               |      0|acc     |0.4471|±  |0.0220|
|                              |       |acc_norm|0.4451|±  |0.0220|
|agieval_lsat_rc               |      0|acc     |0.5762|±  |0.0302|
|                              |       |acc_norm|0.4907|±  |0.0305|
|agieval_sat_en                |      0|acc     |0.7039|±  |0.0319|
|                              |       |acc_norm|0.6942|±  |0.0322|
|agieval_sat_en_without_passage|      0|acc     |0.4369|±  |0.0346|
|                              |       |acc_norm|0.3932|±  |0.0341|
|agieval_sat_math              |      0|acc     |0.3364|±  |0.0319|
|                              |       |acc_norm|0.3091|±  |0.0312|
```
Average: 39.37

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5789|±  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.6694|±  |0.0245|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3953|±  |0.0305|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.3621|±  |0.0254|
|                                                |       |exact_str_match      |0.1309|±  |0.0178|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2920|±  |0.0204|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2043|±  |0.0152|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4300|±  |0.0286|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3140|±  |0.0208|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5010|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6845|±  |0.0104|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4241|±  |0.0234|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.1683|±  |0.0118|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7238|±  |0.0333|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6623|±  |0.0151|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.3770|±  |0.0153|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2208|±  |0.0117|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1514|±  |0.0086|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4300|±  |0.0286|
```
Average: 42.16

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3403|±  |0.0166|
|             |       |mc2   |0.5093|±  |0.0151|
```
