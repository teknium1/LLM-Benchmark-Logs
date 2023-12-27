GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.6220|_  |0.0142|
|             |       |acc_norm|0.6613|_  |0.0138|
|arc_easy     |      0|acc     |0.8699|_  |0.0069|
|             |       |acc_norm|0.8514|_  |0.0073|
|boolq        |      1|acc     |0.8859|_  |0.0056|
|hellaswag    |      0|acc     |0.6752|_  |0.0047|
|             |       |acc_norm|0.8600|_  |0.0035|
|openbookqa   |      0|acc     |0.3640|_  |0.0215|
|             |       |acc_norm|0.4740|_  |0.0224|
|piqa         |      0|acc     |0.8368|_  |0.0086|
|             |       |acc_norm|0.8471|_  |0.0084|
|winogrande   |      0|acc     |0.7687|_  |0.0119|
```
Average: 76.41

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2717|_  |0.0280|
|                              |       |acc_norm|0.2559|_  |0.0274|
|agieval_logiqa_en             |      0|acc     |0.4117|_  |0.0193|
|                              |       |acc_norm|0.4071|_  |0.0193|
|agieval_lsat_ar               |      0|acc     |0.1565|_  |0.0240|
|                              |       |acc_norm|0.1609|_  |0.0243|
|agieval_lsat_lr               |      0|acc     |0.5137|_  |0.0222|
|                              |       |acc_norm|0.5039|_  |0.0222|
|agieval_lsat_rc               |      0|acc     |0.6357|_  |0.0294|
|                              |       |acc_norm|0.6171|_  |0.0297|
|agieval_sat_en                |      0|acc     |0.7864|_  |0.0286|
|                              |       |acc_norm|0.7670|_  |0.0295|
|agieval_sat_en_without_passage|      0|acc     |0.5243|_  |0.0349|
|                              |       |acc_norm|0.5049|_  |0.0349|
|agieval_sat_math              |      0|acc     |0.4545|_  |0.0336|
|                              |       |acc_norm|0.4091|_  |0.0332|
```
Average: 45.32

BigBench:
```
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5579|_  |0.0361|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7263|_  |0.0232|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.4264|_  |0.0308|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.3760|_  |0.0256|
|                                                |       |exact_str_match      |0.1253|_  |0.0175|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.3040|_  |0.0206|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2343|_  |0.0160|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4967|_  |0.0289|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3560|_  |0.0214|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6980|_  |0.0103|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.5759|_  |0.0234|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2886|_  |0.0143|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.6796|_  |0.0348|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6481|_  |0.0152|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.6960|_  |0.0146|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2360|_  |0.0120|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1617|_  |0.0088|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4967|_  |0.0289|
```
Average: 46.99

TruthfulQA:
```
hf-causal-experimental (pretrained=mistralAI/Mixtral-8x7B-Instruct-v0.1,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 480
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.5018|_  |0.0175|
|             |       |mc2   |0.6457|_  |0.0155|
```