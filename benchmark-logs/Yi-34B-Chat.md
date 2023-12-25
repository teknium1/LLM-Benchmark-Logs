GPT4All:
```
hf-causal-experimental (pretrained=01-ai/Yi-34B-Chat,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 14
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5427|_  |0.0146|
|             |       |acc_norm|0.5478|_  |0.0145|
|arc_easy     |      0|acc     |0.8089|_  |0.0081|
|             |       |acc_norm|0.7412|_  |0.0090|
|boolq        |      1|acc     |0.8997|_  |0.0053|
|hellaswag    |      0|acc     |0.6143|_  |0.0049|
|             |       |acc_norm|0.8068|_  |0.0039|
|openbookqa   |      0|acc     |0.3720|_  |0.0216|
|             |       |acc_norm|0.4800|_  |0.0224|
|piqa         |      0|acc     |0.7971|_  |0.0094|
|             |       |acc_norm|0.7982|_  |0.0094|
|winogrande   |      0|acc     |0.7751|_  |0.0117|
```
Average: 72.13

AGIEval:
```
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.3110|_  |0.0291|
|                              |       |acc_norm|0.3228|_  |0.0294|
|agieval_logiqa_en             |      0|acc     |0.4593|_  |0.0195|
|                              |       |acc_norm|0.4178|_  |0.0193|
|agieval_lsat_ar               |      0|acc     |0.2391|_  |0.0282|
|                              |       |acc_norm|0.2261|_  |0.0276|
|agieval_lsat_lr               |      0|acc     |0.6039|_  |0.0217|
|                              |       |acc_norm|0.5275|_  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.7361|_  |0.0269|
|                              |       |acc_norm|0.6766|_  |0.0286|
|agieval_sat_en                |      0|acc     |0.8398|_  |0.0256|
|                              |       |acc_norm|0.8107|_  |0.0274|
|agieval_sat_en_without_passage|      0|acc     |0.5097|_  |0.0349|
|                              |       |acc_norm|0.4757|_  |0.0349|
|agieval_sat_math              |      0|acc     |0.4682|_  |0.0337|
|                              |       |acc_norm|0.3909|_  |0.0330|
```
Average: 48.10


TruthfulQA:
```hf-causal-experimental (pretrained=01-ai/Yi-34B-Chat,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 60
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.3905|_  |0.0171|
|             |       |mc2   |0.5540|_  |0.0155|
```

Note: Some kind of error kept occurring with BigBench on this model, so none is recorded