GPT4All:
```
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5606|_  |0.0145|
|             |       |acc_norm|0.5947|_  |0.0143|
|arc_easy     |      0|acc     |0.8283|_  |0.0077|
|             |       |acc_norm|0.8190|_  |0.0079|
|boolq        |      1|acc     |0.8676|_  |0.0059|
|hellaswag    |      0|acc     |0.6477|_  |0.0048|
|             |       |acc_norm|0.8303|_  |0.0037|
|openbookqa   |      0|acc     |0.3540|_  |0.0214|
|             |       |acc_norm|0.4580|_  |0.0223|
|piqa         |      0|acc     |0.8248|_  |0.0089|
|             |       |acc_norm|0.8319|_  |0.0087|
|winogrande   |      0|acc     |0.7585|_  |0.0120|
```
Average: 73.71

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.2480|_  |0.0272|
|                              |       |acc_norm|0.2244|_  |0.0262|
|agieval_logiqa_en             |      0|acc     |0.3748|_  |0.0190|
|                              |       |acc_norm|0.3794|_  |0.0190|
|agieval_lsat_ar               |      0|acc     |0.2174|_  |0.0273|
|                              |       |acc_norm|0.1957|_  |0.0262|
|agieval_lsat_lr               |      0|acc     |0.3980|_  |0.0217|
|                              |       |acc_norm|0.4020|_  |0.0217|
|agieval_lsat_rc               |      0|acc     |0.5539|_  |0.0304|
|                              |       |acc_norm|0.5167|_  |0.0305|
|agieval_sat_en                |      0|acc     |0.7524|_  |0.0301|
|                              |       |acc_norm|0.7282|_  |0.0311|
|agieval_sat_en_without_passage|      0|acc     |0.4806|_  |0.0349|
|                              |       |acc_norm|0.4126|_  |0.0344|
|agieval_sat_math              |      0|acc     |0.3909|_  |0.0330|
|                              |       |acc_norm|0.3545|_  |0.0323|
```
Average: 40.17

BigBench:
```hf-causal-experimental (pretrained=cognitivecomputations/dolphin-2.6-mixtral-8x7b,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 32
|                      Task                      |Version|       Metric        |Value |   |Stderr|
|------------------------------------------------|------:|---------------------|-----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|0.5789|_  |0.0359|
|bigbench_date_understanding                     |      0|multiple_choice_grade|0.7182|_  |0.0235|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|0.5194|_  |0.0312|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|0.1448|_  |0.0186|
|                                                |       |exact_str_match      |0.0000|_  |0.0000|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|0.2640|_  |0.0197|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|0.2129|_  |0.0155|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|0.4200|_  |0.0285|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|0.3940|_  |0.0219|
|bigbench_navigate                               |      0|multiple_choice_grade|0.5000|_  |0.0158|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|0.6640|_  |0.0106|
|bigbench_ruin_names                             |      0|multiple_choice_grade|0.5491|_  |0.0235|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|0.2595|_  |0.0139|
|bigbench_snarks                                 |      0|multiple_choice_grade|0.7514|_  |0.0322|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|0.6004|_  |0.0156|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|0.4010|_  |0.0155|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|0.2256|_  |0.0118|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|0.1571|_  |0.0087|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|0.4200|_  |0.0285|
```
Average: 43.22

TruthfulQA:
```
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3892|_  |0.0171|
|             |       |mc2   |0.5478|_  |0.0150|
```
