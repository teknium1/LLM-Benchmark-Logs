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