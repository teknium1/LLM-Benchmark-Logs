GPT4All:
```
|    Tasks     |Version|Filter|  Metric  |Value |   |Stderr|
|--------------|-------|------|----------|-----:|---|------|
|arc_challenge |Yaml   |none  |acc       |0.5026|   |      |
|              |       |none  |acc_norm  |0.5384|   |      |
|arc_easy      |Yaml   |none  |acc       |0.8085|   |      |
|              |       |none  |acc_norm  |0.7946|   |      |
|boolq         |Yaml   |none  |acc       |0.8358|   |      |
|hellaswag     |Yaml   |none  |acc       |0.6123|   |      |
|              |       |none  |acc_norm  |0.8102|   |      |
|openbookqa    |Yaml   |none  |acc       |0.3220|   |      |
|              |       |none  |acc_norm  |0.4420|   |      |
|piqa          |Yaml   |none  |acc       |0.8074|   |      |
|              |       |none  |acc_norm  |0.8210|   |      |
|winogrande    |Yaml   |none  |acc       |0.7395|   |      |
```
Average: 71.16

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2244|±  |0.0262|
|                              |       |acc_norm|0.2520|±  |0.0273|
|agieval_logiqa_en             |      0|acc     |0.2657|±  |0.0173|
|                              |       |acc_norm|0.3164|±  |0.0182|
|agieval_lsat_ar               |      0|acc     |0.2304|±  |0.0278|
|                              |       |acc_norm|0.2217|±  |0.0275|
|agieval_lsat_lr               |      0|acc     |0.3373|±  |0.0210|
|                              |       |acc_norm|0.2922|±  |0.0202|
|agieval_lsat_rc               |      0|acc     |0.4238|±  |0.0302|
|                              |       |acc_norm|0.3197|±  |0.0285|
|agieval_sat_en                |      0|acc     |0.5243|±  |0.0349|
|                              |       |acc_norm|0.4854|±  |0.0349|
|agieval_sat_en_without_passage|      0|acc     |0.3981|±  |0.0342|
|                              |       |acc_norm|0.3107|±  |0.0323|
|agieval_sat_math              |      0|acc     |0.3000|±  |0.0310|
|                              |       |acc_norm|0.2545|±  |0.0294|
```
Average: 30.65

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
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1729|±  |0.0143|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.3633|±  |0.0278|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3280|±  |0.0210|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.4510|±  |0.0111|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3281|±  |0.0222|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2054|±  |0.0128|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5414|±  |0.0371|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.4970|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.2720|±  |0.0141|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2280|±  |0.0119|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1486|±  |0.0085|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.3633|±  |0.0278|
```
Average: 34.92

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.2815|±  |0.0157|
|             |       |mc2   |0.4263|±  |0.0142|
```