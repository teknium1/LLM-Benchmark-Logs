GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.6067|_  |0.0143|
|             |       |acc_norm|0.6416|_  |0.0140|
|arc_easy     |      0|acc     |0.8594|_  |0.0071|
|             |       |acc_norm|0.8569|_  |0.0072|
|boolq        |      1|acc     |0.8859|_  |0.0056|
|hellaswag    |      0|acc     |0.6407|_  |0.0048|
|             |       |acc_norm|0.8388|_  |0.0037|
|openbookqa   |      0|acc     |0.3520|_  |0.0214|
|             |       |acc_norm|0.4760|_  |0.0224|
|piqa         |      0|acc     |0.8215|_  |0.0089|
|             |       |acc_norm|0.8303|_  |0.0088|
|winogrande   |      0|acc     |0.7908|_  |0.0114|
```
Average: 76.00%

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.3189|_  |0.0293|
|                              |       |acc_norm|0.2953|_  |0.0287|
|agieval_logiqa_en             |      0|acc     |0.5438|_  |0.0195|
|                              |       |acc_norm|0.4977|_  |0.0196|
|agieval_lsat_ar               |      0|acc     |0.2696|_  |0.0293|
|                              |       |acc_norm|0.2087|_  |0.0269|
|agieval_lsat_lr               |      0|acc     |0.7078|_  |0.0202|
|                              |       |acc_norm|0.6255|_  |0.0215|
|agieval_lsat_rc               |      0|acc     |0.7807|_  |0.0253|
|                              |       |acc_norm|0.7063|_  |0.0278|
|agieval_sat_en                |      0|acc     |0.8689|_  |0.0236|
|                              |       |acc_norm|0.8447|_  |0.0253|
|agieval_sat_en_without_passage|      0|acc     |0.5194|_  |0.0349|
|                              |       |acc_norm|0.4612|_  |0.0348|
|agieval_sat_math              |      0|acc     |0.4409|_  |0.0336|
|                              |       |acc_norm|0.3818|_  |0.0328|
```
Average: 50.27%

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5737|_  |0.0360|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7263|_  |0.0232|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3953|_  |0.0305|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.4457|_  |0.0263|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2820|_  |0.0201|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2186|_  |0.0156|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4733|_  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.5200|_  |0.0224|
|bigbench_navigate                               |      0|multiple_choice_grade|0.4910|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.7495|_  |0.0097|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.5938|_  |0.0232|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.3808|_  |0.0154|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.8066|_  |0.0294|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.5101|_  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.3850|_  |0.0154|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2160|_  |0.0116|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1634|_  |0.0088|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4733|_  |0.0289|
```
Average: 46.69%

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4333|_  |0.0173|
|             |       |mc2   |0.6034|_  |0.0149|
```