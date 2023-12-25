TruthfulQA:
```hf-causal-experimental (pretrained=Qwen/Qwen-72B,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 20
|    Task     |Version|Metric|Value |   |Stderr|
|-------------|------:|------|-----:|---|-----:|
|truthfulqa_mc|      1|mc1   |0.4259|±  |0.0173|
|             |       |mc2   |0.6016|±  |0.0146|
```

GPT4All:
```hf-causal-experimental (pretrained=Qwen/Qwen-72B,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 20
|    Task     |Version| Metric |Value |   |Stderr|
|-------------|------:|--------|-----:|---|-----:|
|arc_challenge|      0|acc     |0.5162|±  |0.0146|
|             |       |acc_norm|0.5435|±  |0.0146|
|arc_easy     |      0|acc     |0.8081|±  |0.0081|
|             |       |acc_norm|0.7542|±  |0.0088|
|boolq        |      1|acc     |0.8804|±  |0.0057|
|hellaswag    |      0|acc     |0.6560|±  |0.0047|
|             |       |acc_norm|0.8490|±  |0.0036|
|openbookqa   |      0|acc     |0.3480|±  |0.0213|
|             |       |acc_norm|0.4720|±  |0.0223|
|piqa         |      0|acc     |0.8194|±  |0.0090|
|             |       |acc_norm|0.8259|±  |0.0088|
|winogrande   |      0|acc     |0.7774|±  |0.0117|
```
Average: 72.89

AGIEval:
```hf-causal-experimental (pretrained=Qwen/Qwen-72B,dtype=float16,trust_remote_code=True,use_accelerate=True), limit: None, provide_description: False, num_fewshot: 0, batch_size: 20
|             Task             |Version| Metric |Value |   |Stderr|
|------------------------------|------:|--------|-----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |0.3346|±  |0.0297|
|                              |       |acc_norm|0.3307|±  |0.0296|
|agieval_logiqa_en             |      0|acc     |0.3978|±  |0.0192|
|                              |       |acc_norm|0.4055|±  |0.0193|
|agieval_lsat_ar               |      0|acc     |0.2391|±  |0.0282|
|                              |       |acc_norm|0.2739|±  |0.0295|
|agieval_lsat_lr               |      0|acc     |0.4941|±  |0.0222|
|                              |       |acc_norm|0.4647|±  |0.0221|
|agieval_lsat_rc               |      0|acc     |0.5019|±  |0.0305|
|                              |       |acc_norm|0.4758|±  |0.0305|
|agieval_sat_en                |      0|acc     |0.7524|±  |0.0301|
|                              |       |acc_norm|0.7184|±  |0.0314|
|agieval_sat_en_without_passage|      0|acc     |0.5000|±  |0.0349|
|                              |       |acc_norm|0.4320|±  |0.0346|
|agieval_sat_math              |      0|acc     |0.4364|±  |0.0335|
|                              |       |acc_norm|0.3182|±  |0.0315|```
Average: 42.74

NOTE: QWEN has issues with BigBench in eval harness, so it was not done