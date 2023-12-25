TruthfulQA:
```hf-causal-experimental (pretrained=upstage/SOLAR-10.7B-v1.0,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 60
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3182|±  |0.0163|
|             |       |mc2   |0.4565|±  |0.0144|```

GPT4All:
```hf-causal-experimental (pretrained=upstage/SOLAR-10.7B-v1.0,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 14
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5247|±  |0.0146|
|             |       |acc_norm|0.5708|±  |0.0145|
|arc_easy     |      0|acc     |0.8148|±  |0.0080|
|             |       |acc_norm|0.8072|±  |0.0081|
|boolq        |      1|acc     |0.8254|±  |0.0066|
|hellaswag    |      0|acc     |0.6394|±  |0.0048|
|             |       |acc_norm|0.8310|±  |0.0037|
|openbookqa   |      0|acc     |0.3240|±  |0.0210|
|             |       |acc_norm|0.4400|±  |0.0222|
|piqa         |      0|acc     |0.8058|±  |0.0092|
|             |       |acc_norm|0.8194|±  |0.0090|
|winogrande   |      0|acc     |0.7459|±  |0.0122|```
Average: 71.99

AGIEval:
```hf-causal-experimental (pretrained=upstage/SOLAR-10.7B-v1.0,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 16
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2520|±  |0.0273|
|                              |       |acc_norm|0.2638|±  |0.0277|
|agieval_logiqa_en             |      0|acc     |0.3748|±  |0.0190|
|                              |       |acc_norm|0.3840|±  |0.0191|
|agieval_lsat_ar               |      0|acc     |0.2217|±  |0.0275|
|                              |       |acc_norm|0.2087|±  |0.0269|
|agieval_lsat_lr               |      0|acc     |0.4353|±  |0.0220|
|                              |       |acc_norm|0.3902|±  |0.0216|
|agieval_lsat_rc               |      0|acc     |0.5911|±  |0.0300|
|                              |       |acc_norm|0.4684|±  |0.0305|
|agieval_sat_en                |      0|acc     |0.7524|±  |0.0301|
|                              |       |acc_norm|0.6942|±  |0.0322|
|agieval_sat_en_without_passage|      0|acc     |0.4223|±  |0.0345|
|                              |       |acc_norm|0.3883|±  |0.0340|
|agieval_sat_math              |      0|acc     |0.3727|±  |0.0327|
|                              |       |acc_norm|0.3136|±  |0.0314|```
Average: 38.89

BigBench:
```hf-causal-experimental (pretrained=upstage/SOLAR-10.7B-v1.0,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 32
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5368|±  |0.0363|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7046|±  |0.0238|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.3760|±  |0.0302|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1950|±  |0.0209|
|                                                |       |exact_str_match      |0.1058|±  |0.0163|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2520|±  |0.0194|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.1914|±  |0.0149|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.3967|±  |0.0283|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3340|±  |0.0211|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|±  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.5150|±  |0.0112|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.3817|±  |0.0230|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2445|±  |0.0136|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.5746|±  |0.0369|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.4970|±  |0.0159|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.4640|±  |0.0158|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2344|±  |0.0120|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1640|±  |0.0089|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.3967|±  |0.0283|
```
Average: 38.66