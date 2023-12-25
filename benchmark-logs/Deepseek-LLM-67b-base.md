GPT4All:
```hf-causal-experimental (pretrained=deepseek-ai/deepseek-llm-67b-base,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 20
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5589|±  |0.0145|
|             |       |acc_norm|0.5964|±  |0.0143|
|arc_easy     |      0|acc     |0.8405|±  |0.0075|
|             |       |acc_norm|0.8316|±  |0.0077|
|boolq        |      1|acc     |0.8486|±  |0.0063|
|hellaswag    |      0|acc     |0.6502|±  |0.0048|
|             |       |acc_norm|0.8437|±  |0.0036|
|openbookqa   |      0|acc     |0.3620|±  |0.0215|
|             |       |acc_norm|0.4800|±  |0.0224|
|piqa         |      0|acc     |0.8226|±  |0.0089|
|             |       |acc_norm|0.8335|±  |0.0087|
|winogrande   |      0|acc     |0.8074|±  |0.0111|
```
Average: 74.87

AGIEval:
```hf-causal-experimental (pretrained=deepseek-ai/deepseek-llm-67b-base,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 20
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2756|±  |0.0281|
|                              |       |acc_norm|0.2559|±  |0.0274|
|agieval_logiqa_en             |      0|acc     |0.3763|±  |0.0190|
|                              |       |acc_norm|0.3518|±  |0.0187|
|agieval_lsat_ar               |      0|acc     |0.2217|±  |0.0275|
|                              |       |acc_norm|0.2000|±  |0.0264|
|agieval_lsat_lr               |      0|acc     |0.4294|±  |0.0219|
|                              |       |acc_norm|0.3569|±  |0.0212|
|agieval_lsat_rc               |      0|acc     |0.5874|±  |0.0301|
|                              |       |acc_norm|0.4461|±  |0.0304|
|agieval_sat_en                |      0|acc     |0.7816|±  |0.0289|
|                              |       |acc_norm|0.6262|±  |0.0338|
|agieval_sat_en_without_passage|      0|acc     |0.4951|±  |0.0349|
|                              |       |acc_norm|0.3641|±  |0.0336|
|agieval_sat_math              |      0|acc     |0.4227|±  |0.0334|
|                              |       |acc_norm|0.3455|±  |0.0321|
```
Average: 36.83

BigBench:
```hf-causal-experimental (pretrained=deepseek-ai/deepseek-llm-67b-base,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 20
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5789|±  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7317|±  |0.0231|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3140|±  |0.0289|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1281|±  |0.0177|
|                                                |       |exact_str_match      |0.0000|±  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2820|±  |0.0201|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2000|±  |0.0151|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4333|±  |0.0287|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3460|±  |0.0213|
|bigbench_navigate                               |      0|multiple_choice_grade|0.4720|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.5175|±  |0.0112|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.4688|±  |0.0236|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.3216|±  |0.0148|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6298|±  |0.0360|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6298|±  |0.0154|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.4470|±  |0.0157|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2096|±  |0.0115|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1480|±  |0.0085|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4333|±  |0.0287|```
Average: 40.51